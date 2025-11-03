# Go and Gin Framework Test Project
To install a package manager into your project (if you haven't already), first you need to run this command:

```jsx
go mod init <myapp>
```

This will create the `go.mod` file with the version of Go that is being used

Then use the following command to import a module (like NPM or nuget)

```jsx
go get github.com/gin-gonic/gin
```

This will update the `go.mod` file together with creating a `go.sum` file