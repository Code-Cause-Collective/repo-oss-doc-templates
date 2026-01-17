> [!NOTE]
> This documentation provides an opinionated framework rather than a rigid standard
> We invite you to adapt and expand on this information as you continue your learning journey and refine your own approach.

# SimpleGram

SimpleGram is an opinionated tool for handling word plurals

![Static Badge](https://img.shields.io/badge/npm-v1.0.0-blue) ![Static Badge](https://img.shields.io/badge/ci-passing-brightgreen?logo=github)

## Documentation

For more detailed documentation, please visit the dedicated [SimpleGram API Reference](docs/api-reference/README.md).

## Installation

SimpleGram is available as a NPM package.

```bash
npm install simplegram
```

## Usage

```javaScript
import gram from 'simplegram';

gram.plural('apple');   // 'apples'
gram.singular('cars');  // 'car'
```

## Contributing

If you have suggestions for how this project could be improved, or want to report a bug, feel free to open an issue! We welcome all contributions.

Likewise, before contributing please read the [contribution guide](CONTRIBUTING.md).

## Resources

- [Changelog](CHANGELOG.md)
- [Code of Conduct](CODE_OF_CONDUCT.md)
- [Contributing](CONTRIBUTING.md)
- [Security](SECURITY.md)
- [API Reference](docs/api-reference/README.md)

## License

[MIT](LICENSE)
