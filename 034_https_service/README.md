

1. src/main/resources folder --> keytool -genkey -alias key-alias -keystore keystore-name.jks -keyalg RSA -storetype JKS

2. HTTP Listener --> HTTPS, 8082 --> TLS config --> key-store configuration as per the above command