FROM mcr.microsoft.com/windows/servercore/iss
RUN powershell -NoProfile -Command Remove-Item -recurse C:\inetpub\wwwroot\*
WORKDIR /inetpub/wwwroot
COPY content/ .