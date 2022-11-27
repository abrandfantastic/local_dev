# local development environment
# mkcert needs to be installed using HomeBrew if using MacOS
# brew install mkcert
# mkcert - install
# cert directory needs to be created
# mkdir -p certs
# mkcert -cert-file certs/local-cert.pem -key-file certs/local-key.pem "app.localhost" "*.app.localhost" "wp.local" "*.wp.local"
# confirm location of cert keys: mkcert -CAROOT


# to uninstall mkcert
# mkcert -uninstall
# rm -r "$(mkcert -CAROOT)"
