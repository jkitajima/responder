<h1 align="center">Responder</h1> <br>
<p align="center">
    <img alt="Gopher refining a speech text before the real presentation" title="Gopher" src="./assets/gopher.png" width="320">
</p>

<p align="center">
    Helper module to encode HTTP API responses
</p>

---

## Introduction

This module contains helper functions and structs to respond API calls in accordance to this [HTTP API Design](https://github.com/jkitajima/http_api_design).


## General Structure

There are three files:
- `decoder.go`: responsible for decoding incoming JSON API requests
- `response.go`: contains the structs explained by the API Design document
- `responder.go`: contains the functions that send the response to the client


## License

Distributed under the `GNU Lesser General Public License, version 2.1`. See LICENSE file for more information.
