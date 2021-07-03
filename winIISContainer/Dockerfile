FROM mcr.microsoft.com/windows/servercore/iis:windowsservercore-20H2
RUN powershell -NoProfile -Command Remove-Item -recurse C:\inetpub\wwwroot\*
WORKDIR /inetpub/wwwroot
COPY . /inetpub/wwwroot