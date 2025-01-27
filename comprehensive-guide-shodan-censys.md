# A Comprehensive Guide to Using Shodan & Censys

# A Comprehensive Guide to Using Shodan & Censys

**Shodan** and **Censys** are search engines used to find internet-connected devices and services, such as servers, cameras, and networking equipment. They are primarily used for security analysis and discovering vulnerabilities in internet-connected systems.

## Shodan:

### Basic search operators:

**[WITH-OUT-SPEACE]**

**Network:**

- From this host:
    - `ip:127.0.0.1`

Search for a device using a specific IP address.

- On this port:
    - `port:22,8080`

Search for devices that use specific ports.

- ASN:
    - `asn:1234`

Search for devices that belong to a network or ISP using a specific ASN.

- On this hostname:
    - `hostname:google.com`

Search for devices using a specific domain name.

- From organization:
    - `org:"Google LLC"`

Search for devices managed or owned by a specific organization.

- ISP:
    - `isp:"Korea Telecom"`

Search for devices managed by a specific Internet Service Provider.

- Has IPv6:
    - `has_ipv6:false`

Search for devices that support or don't support IPv6.

---

**Location:**

- In state:
    - `state:California`

Search for devices located in a specific state.

- From city:
    - `city:"San Diego"`

Search for devices located in a specific city.

- With country code:
    - `country:US`

Search for devices located in a specific country, identified by its country code.

- Postal code:
    - `postal:10001`

Search for devices located in a specific postal/ZIP code area.

- Region code:
    - `region:NY`

Search for devices located in a specific region (often used for US states or specific geographical regions).

---

**Metadata:**

- Running this software/ product:
    - `product:Apache`

Search for devices running a specific software or product.

- On version:
    - `version:2.4.6`

Search for devices running a specific version of software or a product.

- Operating System:
    - `os:Windows`

Search for devices running a specific operating system.

- Numeric hash of the "data" property:
    - `hash:-553166942`

Search for devices based on a numeric hash of a specific data property.

- CPE:
    - `cpe:2.3:a:wordpress:wordpress`

Search for devices using a specific CPE identifier, which represents a particular software, hardware, or operating system.

- With this device type:
    - `device:router`

Search for devices of a specific type (e.g., router, server, etc.).

---

**HTTP:**

- With these words in the HTML of the frontpage:
    - `http.html:Apache`

Search for devices that contain specific words in the HTML of the frontpage.

- With this HTTP status:
    - `http.status:401`

Search for devices that use a specific HTTP status (e.g., 401 Unauthorized).

- Web technologies:
    - `http.component:php`

Search for devices that use specific web technologies (e.g., PHP).

- Within the category of web technologies:
    - `http.component_category:javascript`

Search for devices that use technologies within a specific category of web technologies (e.g., JavaScript).

- HTML hash:
    - `http.html_hash:94098888`

Search for devices based on the HTML hash of a webpage.

- With these words in the title:
    - `http.title:"Welcome to nginx”`

Search for devices that contain specific words in the title of the page.

- HTTP headers hash:
    - `http.headers_hash:735712792`

Search for devices based on the hash of HTTP headers.

- Favicon hash:
    - `http.favicon.hash:999357577`

Search for devices based on the hash of the website’s favicon.

- Robots.txt hash:
    - `http.robots_hash:-1022729730`

Search for devices based on the hash of the robots.txt file.

- Using this Web Application Firewall:
    - `http.waf:Cloudfront`

Search for devices that use a specific Web Application Firewall (e.g., Cloudfront).

---

**SSL/ TLS:**

- Has a SSL/ TLS certificate:
    - `has_ssl:true`

Search for devices that have an SSL/TLS certificate.

- Is certificate expired:
    - `ssl.cert.expired:true`

Search for devices with an expired SSL/TLS certificate.

- SSL/ TLS versions that the service supports:
    - `ssl.version:sslv3`

Search for devices based on the SSL/TLS versions supported by the service.

- Subject's CN:
    - [`ssl.cert.subject.cn](http://ssl.cert.subject.cn/):google.com`

Search for devices based on the Common Name (CN) in the SSL/TLS certificate subject.

- Issuer's CN:
    - [`ssl.cert.issuer.cn](http://ssl.cert.issuer.cn/):kubernetes`

Search for devices based on the Common Name (CN) in the SSL/TLS certificate issuer.

- SHA1 hash of certificate:
    - `ssl.cert.fingerprint:fa2145dc4d9403a3097751784a21f2c56d94be52`

Search for devices based on the SHA1 hash of their SSL/TLS certificate.

- Public key's bits:
    - `ssl.cert.pubkey.bits:2048`

Search for devices based on the number of bits in their SSL/TLS public key.

- Public key's type:
    - `ssl.cert.pubkey.type:ssh-rsa`
    - `ssl.cert.serial:10333644429771748086102214072353968797`

Search for devices based on the type of their SSL/TLS public key.

Search for devices based on the serial number of their SSL/TLS certificate.

- Chain count:
    - `ssl.chain_count:16`

Search for devices based on the number of certificates in their SSL/TLS certificate chain.

- Cipher's secret bits:
    - `ssl.cipher.bits:256`

Search for devices based on the number of secret bits in their SSL/TLS cipher.

- Cipher's version:
    - `ssl.cipher.version:SSLv3`

Search for devices based on the version of the SSL/TLS cipher they use.

- JA3S:
    - `ssl.ja3s:39e9c15bbfeb1b802cc66aad25c479d3`

Search for devices based on the JA3S hash, which is a fingerprint for SSL/TLS client configurations.

- JARM:
    - `ssl.jarm:29d29d00029d29d21c41d41d00041d0fc7ac8335432249e8becb757baaacec`

Search for devices based on the JARM fingerprint, which is a method of identifying SSL/TLS servers.

---

**Screenshot:**

- Has screenshot:
    - `has_screenshot:true`

Search for devices that have a screenshot.

- Classified as the following type of image based on machine learning:
    - `screenshot.label:login`

Search for devices that have been classified as a specific type of image using machine learning (e.g., login page image).

- Numeric hash of the image data:
    - `screenshot.hash:997449809`

Search for devices based on the numeric hash of the image data.

---

**Cloud:**

- Name of the cloud provider:
    - `cloud.provider:Amazon`
- In region:
    - `cloud.region:us-east-1`

---

### Advanced search operators:

Waiting... ⏳😊

---

## Censys:

Waiting... ⏳😊

---

**Note: I will keep it updated always (Insha'Allah) 😊✨**

You can follow me on Platform X: [iProgrammer16](https://x.com/iProgrammer16), [1ZeroDay](https://x.com/1ZeroDay) 📱, Github: [iProgrammer16](https://github.com/iProgrammer16) 👾,and on YouTube: [Youtube](https://www.youtube.com/@iProgrammer16) 🎥.