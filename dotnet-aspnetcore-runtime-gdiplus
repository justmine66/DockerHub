FROM microsoft/dotnet:2.2.0-aspnetcore-runtime
RUN apt-get update -y && apt-get install -y libgdiplus lsof && apt-get install -y libc6-dev
RUN ln -s /usr/lib/libgdiplus.so /usr/lib/gdiplus.dll
