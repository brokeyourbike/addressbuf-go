# addressbuf-go
AddressBook protobuf example in Go

# Build

```bash
protoc --go_out=. --go_opt=paths=source_relative pb/addressbook.proto
```

# Use

```bash
go run cmd/add_person/add_person.go ./addressbook.data
```

```bash
go run cmd/list_people/list_people.go ./addressbook.data
```

# Acknowledgement

Code was stolen from [protobuf examples](https://github.com/protocolbuffers/protobuf/tree/master/examples) for educational purposes.