# alpha-ssl-master
alpha-ssl-master

# alphaSSL (Easy SSL)

alphaSSL is a script to quickly obtain SSL certificates for your domains. It supports both single and multiple domains, and it automatically uses either acme.sh or certbot to generate certificates.

### Features

- **Single Domain**: e.g., `sub.domain.com`
- **Multiple Domains**: e.g., `sub1.domain1.com sub2.domain2.com`
- **Auto Configuration**: Uses acme.sh or certbot
- **Predefined Panel Paths**: Supports `marzban`, `marzneshin`, `x-ui`, `3x-ui`, `s-ui`, `hiddify`
- **Custom Paths**: Specify your own directory

### How to Use

1. **Download and Install the Script:**

   ```bash
   sudo bash -c "$(curl -sL https://github.com/4lph4shell/alpha-ssl-master.git/alphaSSL.sh)" @ --install
   ```

2. **Run the Script:**

<br>
   <img  src="https://github.com/4lph4shell/alpha-ssl-master/blob/master/00.png" />

   <br>
   
   ```bash
   essl <email> <domain1 domain2 ...> <destination>
   ```
   - `<email>`: Your email address for notifications.
   - `<domain1 domain2 ...>`: List of domains to secure.
   - `<destination>`: Path or predefined panel directory (e.g., `marzban`, `x-ui`).

### Examples

- **Single Domain:**

  ```bash
  essl user@example.com example.com /etc/ssl/certs
  ```

- **Multiple Domains:**

  ```bash
  essl user@example.com domain1.com domain2.com /custom/path
  ```

- **Predefined Panel Path:**
  ```bash
  essl user@example.com example.com marzban
  ```

### Additional Commands

- **Upgrade the Script:**

  ```bash
  essl --upgrade
  ```

- **Help:**
  ```bash
  essl --help
  ```

**We don't need financial support, only Star (⭐) is enough, thank you.**
