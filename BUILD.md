Update oauth flag defaults and Add client-secret default value if wanted. (don't check in secret)


For whatever platform currently on:

go build -o k8s-auth


To see possible platforms:

go tool dist list


For MacOS x86:

GOOS=darwin GOARCH=amd64 go build -o k8s-auth.darwin-amd64

MacOS arm64:

GOOS=darwin GOARCH=arm64 go build -o k8s-auth.darwin-arm64



For Windows amd64:

GOOS=windows GOARCH=amd64 go build -o k8s-auth.exe


For linux amd64:

GOOS=linux GOARCH=amd64 go build -o k8s-auth.linux-amd64


