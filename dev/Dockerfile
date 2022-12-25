FROM mcr.microsoft.com/dotnet/sdk:7.0

RUN useradd -m -s $(which bash) mahi
RUN mkdir /app && chown mahi:mahi /app

USER mahi