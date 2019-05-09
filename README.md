# headless-chromoting
Help for Chrome Remote Desktop deployment and activation on headless devices.

## Authorize Chrome Remote Desktop Manually

[Follow this link](https://accounts.google.com/o/oauth2/auth?scope=https://www.googleapis.com/auth/chromoting%20https://www.googleapis.com/auth/googletalk%20https://www.googleapis.com/auth/userinfo.email&redirect_uri=https://talkgadget.google.com/talkgadget/blank&response_type=code&client_id=440925447803-avn2sj1kc099s0r7v62je5s339mu0am1.apps.googleusercontent.com&access_type=offline&approval_prompt=force)

Copy the resulting url containing a *code=* parameter.

Paste it at the prompt `Extracted code:`

## Troubleshooting

You must be able to sudo to run the activation command.

