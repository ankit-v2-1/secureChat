

<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![Twitter][twitter-shield]][twitter-url]



<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/ankit-v2-1/secureChat">
    <img src="images/logo.png" alt="Logo" width="150" height="150">
  </a>

  <h3 align="center">SecureChat</h3>

  <p align="center">
    Cryptography project in which messages are encrypted using AES!
    <br />
    <a href="https://github.com/ankit-v2-1/secureChat"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/ankit-v2-1/secureChat">View Demo</a>
    ·
    <a href="https://github.com/ankit-v2-1/secureChat/issues">Report Bug</a>
    ·
    <a href="https://github.com/ankit-v2-1/secureChat/issues">Request Feature</a>
  </p>
</p>





<!-- ABOUT THE PROJECT -->
## About The Project
SecureChat is a simple cryptography project in which messages are encrypted using AES. AES is an iterative rather than Feistel cipher. It is based on ‘substitution–permutation network’. It comprises of a series of linked operations, some of which involve replacing inputs by specific outputs (substitutions) and others involve shuffling bits around (permutations).

AES performs all its computations on bytes rather than bits. Hence, AES treats the 128 bits of a plaintext block as 16 bytes. These 16 bytes are arranged in four columns and four rows for processing as a matrix −

The features of AES are as follows −

 * Symmetric key symmetric block cipher
 * 128-bit data, 128/192/256-bit keys
 * Stronger and faster than Triple-DES
 * Provide full specification and design details
 * Software implementable in C and Java

<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.
  ```sh
   $ git clone https://github.com/ankit-v2-1/secureChat.git
   $ cd secureChat
   ```

### Dependencies
Creating Virtual Environment:
```
$ python3 -m pip install --user virtualenv
$ python3 -m venv env
$ source env/bin/activate
```
Installing Dependencies:
```
$ pip3 install -r requirements.txt
```

```
Running server
$ python3 server.py

Running client
$python3 client.py
```



<!-- USAGE EXAMPLES -->
## Usage



_For more examples, please refer to the [Documentation](https://example.com)_



<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/ankit-v2-1/secureChat/issues) for a list of proposed features (and known issues).



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.





<!-- ACKNOWLEDGEMENTS -->







<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/ankit-v2-1/CypherChat.svg?style=for-the-badge
[contributors-url]: https://github.com/ankit-v2-1/CypherChat/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/ankit-v2-1/CypherChat.svg?style=for-the-badge
[forks-url]: https://github.com/ankit-v2-1/CypherChat/network/members
[stars-shield]: https://img.shields.io/github/stars/ankit-v2-1/CypherChat.svg?style=for-the-badge
[stars-url]: https://github.com/ankit-v2-1/CypherChat/stargazers
[issues-shield]: https://img.shields.io/github/issues/ankit-v2-1/CypherChat.svg?style=for-the-badge
[issues-url]: https://github.com/ankit-v2-1/CypherChat/issues
[license-shield]: https://img.shields.io/github/license/ankit-v2-1/CypherChat.svg?style=for-the-badge
[license-url]: https://github.com/ankit-v2-1/CypherChat/blob/master/LICENSE.txt
[twitter-shield]: https://img.shields.io/twitter/follow/ankit_v2_1?style=for-the-badge&color=09f&labelColor=black.svg&logo=twitter&label=@ankit_v2_1
[twitter-url]: https://twitter.com/ankit_v2_1
[product-screenshot]: images/screenshot.png
