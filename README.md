# BasicCookieSecurity
This project is available in both English and Chinese.

- [English Version](README.md)
- [中文版](README.zh.md)

## Introduction
**BasicCookieSecurity** is a project to document and share my learning about cookie security practices in web development. It covers basic cookie security knowledge and best practices to help developers use and manage cookies correctly and securely in web applications.

## Content
In this project, I’ve summarized some fundamental cookie security knowledge, including but not limited to the following:
- **HTTPOnly and Secure flags**: Ensures cookies are not accessible via JavaScript and can only be transmitted over HTTPS connections.
- **SameSite attribute**: Prevents Cross-Site Request Forgery (CSRF) attacks by limiting cross-site cookie transmissions.
- **Cookie expiration**: Sets a reasonable expiration time to avoid storing sensitive information for too long.
- **Preventing cookie leakage**: Minimizes the risk of cookies being stolen and exploited through proper configuration.

## How to Use
You can use this repository as a learning resource to understand how to securely use cookies in your own web applications. The sample code and comments in the project demonstrate how to configure cookies securely.

1. Download or clone the project:
    ```bash
    git clone https://github.com/your-username/BCS-BasicCookieSecurity.git
    ```

2. Check the sample code in the `/examples` directory to learn how to apply these security measures in real-world projects.

## Contribution
If you have any suggestions or ideas for improvement, feel free to contribute through a Pull Request.

Steps:
1. Fork the repository
2. Create your branch: `git checkout -b feature/your-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin feature/your-feature`
5. Open a Pull Request

## License
This project is licensed under the MIT License. For more details, please see the [LICENSE](LICENSE) file.
