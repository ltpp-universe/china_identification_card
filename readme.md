<center>

# China Identification Card

[![](https://img.shields.io/crates/v/china_identification_card.svg)](https://crates.io/crates/china_identification_card)
[![](https://docs.rs/china_identification_card/badge.svg)](https://docs.rs/china_identification_card)
[![](https://github.com/ltpp-universe/china_identification_card/workflows/Rust/badge.svg)](https://github.com/ltpp-universe/china_identification_card/actions?query=workflow:Rust)
[![](https://img.shields.io/crates/l/china_identification_card.svg)](./LICENSE)

</center>

[Official Documentation](https://docs.ltpp.vip/CHINA_IDENTIFICATION_CARD/)

A Rust library for validating Chinese identification card numbers based on official rules and checksums.

## Features

- Validates the length and format of a Chinese identification card number
- Calculates and verifies the checksum according to official weight factors
- Lightweight and easy to integrate

## Installation

To use this crate, you can run cmd:

```shell
cargo add china_identification_card
```

## Examples

```rust
use china_identification_card::*;
let is_valid: bool = is_valid_id_number("110101202311012176");
```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## Contact

For any inquiries, please reach out to the author at [ltpp-universe <root@ltpp.vip>](mailto:root@ltpp.vip).
