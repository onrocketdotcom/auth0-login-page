# Auth0 Universal Login Template

The default Auth0 Universal Login page does not display progress indicators after a form has been submitted.

This template adds loading spinners to the form buttons, providing users with visual feedback while they are waiting to be redirected.

## Prerequisites

- **Auth0 CLI**: Ensure you have the Auth0 CLI installed and configured.

## Usage

1. Download the template file.
2. Update your template by running the following command:
   ```bash
   cat universal_login_template.liquid | auth0 universal-login templates update
   ```

## Resources

- [Auth0 Documentation: Customize Universal Login Page Templates](https://auth0.com/docs/customize/login-pages/universal-login/customize-templates)
- [Auth0 CLI Github Project](https://github.com/auth0/auth0-cli)
- [Auth0 CLI Reference: `auth0 universal-login templates`](https://auth0.github.io/auth0-cli/auth0_universal-login_templates.html)

## License

This project is licensed under the MIT License. See the LICENSE file for details.
