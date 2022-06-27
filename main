$ go get google.golang.org/api/tasks/v1
$ go get google.golang.org/api/moderator/v1
$ go get google.golang.org/api/urlshortener/v1
... etc ...
package main

import (
        "context"
        "net/http"

        "google.golang.org/api/urlshortener/v1"
)

func main() {
        ctx := context.Background()
        svc, err := urlshortener.NewService(ctx)
        // ...
}
