# addressbuf-go

[![Maintainability](https://api.codeclimate.com/v1/badges/b7ba26804d274c4da357/maintainability)](https://codeclimate.com/github/brokeyourbike/addressbuf-go/maintainability)
[![Test Coverage](https://api.codeclimate.com/v1/badges/b7ba26804d274c4da357/test_coverage)](https://codeclimate.com/github/brokeyourbike/addressbuf-go/test_coverage)

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