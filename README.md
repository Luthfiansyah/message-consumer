# Warpin Message Consumer

## System Requirement
- Golang go1.12.6

## How to Install ?

Do the following command
```
mkdir -p your_path/warpin-message-consumer
cd your_path/warpin-message-consumer
git clone https://github.com/Luthfiansyah/warpin-message-consumer.git
```

And you should now find the source code under `/warpin-message-consumer` directory.

## Directory Structure

```
  + your_path/
  |
  +--+ config/
  |  |
  |  +--+ config.go
  |     |
  | config.toml
  | executable file warpin-message
```

Get into the `warpin-message-consumer` folder by

```
cd warpin-message-consumer
```

Under that folder you need to run below command to install required library dependency file go.mod

```
go mod init github.com/Luthfiansyah/warpin-message-consumer
go get 
```
Add new dependency
```
go get -u github.com/lorem/ipsum
```

## How to compile and run the code ?
And then following this command :

Just run this command
```
go run client-consumer.go
```

Author Moh Reza Luthfiansyah