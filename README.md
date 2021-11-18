# GitHub Actions Exercise

An exercise for 'DevOps and SRE' on HTW Berlin

## Test
![960348ff78581cb6f0aa587bb750dc07](https://user-images.githubusercontent.com/59999559/142470032-6e3bc217-d10e-4a1b-a26b-05cf2bc3b7cc.jpg)



```bash
go test ./...
```

## Build

```bash
docker build . -t my-app
```

## Run

```bash
docker run -p 8080:8080 my-app
```
