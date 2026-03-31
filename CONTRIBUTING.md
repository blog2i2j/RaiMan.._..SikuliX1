# Contributing to SikuliX

Thanks for your interest in contributing to SikuliX!

## How to contribute

### Reporting bugs

Open an issue on [GitHub Issues](https://github.com/oculix-org/SikuliX1/issues) with:

- Your OS and version
- Java version (`java -version` output)
- SikuliX version
- Steps to reproduce
- Console output with `-v` flag

### Submitting code

1. Fork the repository
2. Create a branch from `master` (`git checkout -b fix/your-fix`)
3. Make your changes
4. Test locally: `mvn clean package -DskipTests`
5. Submit a pull request with a clear description of the change

### Building from source

```bash
# Windows
mvn clean package -Pcomplete-win-jar -DskipTests

# macOS
mvn clean package -Pcomplete-mac-jar -DskipTests

# Linux
mvn clean package -Pcomplete-lux-jar -DskipTests
```

Requires **Java 17** ([Eclipse Temurin](https://adoptium.net/temurin/releases/?version=17) recommended).

### Documentation

Documentation improvements are welcome. You can contribute via pull requests to the repository or to the [GitBook documentation](https://raimans-sikulix.gitbook.io/sikulix.com).

## Guidelines

- Keep pull requests focused on a single change
- Follow existing code style
- Add comments for non-obvious logic
- Test on your platform before submitting

## Questions?

Open a [Discussion](https://github.com/oculix-org/SikuliX1/discussions) on GitHub.
