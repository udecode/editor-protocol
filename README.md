# Editor Protocol

The Editor Protocol is an open standard for building a rich text editor. Editors developed in accordance with the protocol allow you to make applications readable by humans and machines. The protocol features alternatives to cover all use-cases as there is no clear definition of what the standard should be. The choice is yours.

## Getting Started

You can find out the Protocol in the [docs folder](https://github.com/udecode/editor-protocol/tree/main/docs). Each Doc is composed of Specs, one Spec should be mappable to one Unit Test (_"when..., it should be..."_), not less, not more. Each Spec can start with a link to an issue to trace the discussion and development around it.

The large docs will get split into smaller and decoupled docs over time.

## Usage

[Plate](https://github.com/udecode/plate) is an example framework that will follow the Editor Protocol.

## Roadmap

_We’ll be publishing a public roadmap for the Editor Protocol soon._

<!-- See the [open issues](https://github.com/udecode/editor-protocol/issues?q=is%3Aissue+is%3Aopen) for a list of some proposed features (and known issues). -->

### Documentation-Driven Development

The Editor Protocol follows Documentation-Driven Development principles.

The philosophy behind Documentation-Driven Development is a simple: **from the perspective of a user, if a feature is not documented, then it doesn't exist, and if a feature is documented incorrectly, then it's broken.**

- Document the feature *first*. Figure out how you're going to describe the feature to users; if it's not documented, it doesn't exist. Documentation is the best way to define a feature in a user's eyes.
- Whenever possible, documentation should be reviewed by users (community) before any development begins.
- Once documentation has been written, development should commence, and test-driven development is preferred.
- Unit tests should be written that test the features as described by the documentation. If the functionality ever comes out of alignment with the documentation, tests should fail.
- When a feature is being modified, it should be modified documentation-first.
- When documentation is modified, so should be the tests.
- Documentation and software should both be versioned, and versions should match, so someone working with old versions of software should be able to find the proper documentation.

Order of operations for new features:
- Editor Protocol (Documentation-driven development):
  - Open an issue or PR documenting the new feature into [/docs](https://github.com/udecode/editor-protocol/tree/main/docs)
  - Include the issue or PR number at the start of the spec.
  - Review then merge.
  - _Semantic versioning – after beta_
- Application (Test-driven development):
  - Open a PR testing the corresponding Editor Protocol feature, mentioning the issue # number.
  - Develop the feature in that PR so that the unit tests pass.
  - Review then merge.
  - Release.

## Contributing

The Editor Protocol is an open-source standard, and community contributions are what make open-source such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

🌟 Please consider **starring** the project and watching it on GitHub, to be kept abreast of future developments and show your appreciation.

📥 If you’ve got an idea for a new spec, would like to make a suggestion that improves the protocol itself, or want to contribute to a better developer experience for users of the protocol, please open an issue, and feel free to fork the repo in order to create a pull request.

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feat/AmazingFeature`)
3.  Follow the above Documentation-Driven Development steps.

<!-- If you’re looking for inspiration regarding new specs to write, or contributions you could make, please check the [open issues](https://github.com/udecode/editor-protocol/issues?q=is%3Aissue+is%3Aopen). -->

[Become a Sponsor!](https://github.com/sponsors/zbeyens)

Find us on [Slack](https://slate-js.slack.com/messages/plate), we will take the time to guide you.

## License

[MIT](https://github.com/udecode/editor-protocol/blob/main/LICENSE)
