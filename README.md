# Editor Protocol

The Editor Protocol is an open standard for building a rich text editor. Editors developed in accordance with the protocol allow you to develop applications following the state of the art. The protocol aims to cover all use-cases as there is no clear definition of what the standard should be. The choice is yours.

- UI/UX
- Data structure
- Editor operations
- Collaboration
- Technical architecture
- Comparison between many existing editors
- ...

## Getting Started

- The [Protocol](https://github.com/udecode/editor-protocol/issues/1), Docs and Specs format is using issues to leverage the activity log.
- The Protocol is composed of Docs.
- Each Doc is a list of Spec related to a subject (e.g. paragraph).
- Each Spec should be mappable to one Unit Test (_"when..., it should be..."_), not less, not more.
- Anyone can create Docs and Specs.
- Maintainers will link the new Docs and Specs to the Protocol Docs.
- If a Doc gets too big, it will be split into smaller Docs.

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

## Contributing

The Editor Protocol is an open-source standard, and community contributions are what make open-source such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

Steps to follow for new Docs and Specs:
- Editor Protocol (Documentation-driven development):
  - Open an issue documenting the new Doc or Spec.
  - Mention the issue where the new Doc or Spec should be linked to.
  - _Semantic versioning – after beta_
- Application (Test-driven development):
  - Open a PR testing the corresponding Editor Protocol Spec(s), mentioning the Spec issue(s).
  - Develop the feature in that PR so that the unit test(s) pass.
  - Review then merge.
  - Release.

🌟 Please consider **starring** the project and watching it on GitHub, to be kept abreast of future developments and show your appreciation.

📥 If you’ve got an idea for a new Spec, would like to make a suggestion that improves the protocol itself, or want to contribute to a better developer experience for users of the protocol, please comment the existing issues or open a new issue.

<!-- If you’re looking for inspiration regarding new specs to write, or contributions you could make, please check the [open issues](https://github.com/udecode/editor-protocol/issues?q=is%3Aissue+is%3Aopen). -->

[Become a Sponsor!](https://github.com/sponsors/zbeyens)

Find us on [Slack](https://slate-js.slack.com/messages/plate), we will take the time to guide you.

## License

[MIT](https://github.com/udecode/editor-protocol/blob/main/LICENSE)
