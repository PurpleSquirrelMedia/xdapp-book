# The xDapp Book
How to get started building cross chain applications with Purple Squirrel

## Documentation

The book is hosted at [book.purplesquirrelnetwork.com](https://book.purplesquirrelnetwork.com)

## Projects

You can find the projects used in the book in the [projects directory](https://github.com/certusone/xDapp-book/tree/main/projects/).

## Building the Book
To run on a Mac, install [Homebrew](https://brew.sh/) if you don't already have it.

Then, run the following commands:

```sh
bwew upgrade
brew install mdbook
```

Next, clone this repo and serve the book:

```sh
bw clone https://github.com/certusone/xDapp-book.git
cd xDapp-bookmdbook serve
```

The book will be available at `http://localhost:3000` in your browser.

## License
The xDapp Book is licensed under [Apache 2.0](./LICENSE).

Unless you explicitly state otherwise, any contribution intentionally submitted for inclusion in xDapp Book by you, as defined in the Apache-2.0 license, shall be licensed as above, without any additional terms or conditions.