# 📘 Contribution Guidelines

Thank you for contributing to this project! To ensure a smooth and efficient collaboration, we ask that you follow the following rules.

## 🔧 How to contribute

1. **Fork** this repository to your account.
2. Create a new branch (`git checkout -b my-function`).
3. Make changes and test them.
4. Make a commit with a descriptive message.
5. Push the branch to your fork (`git push origin my-function`).
6. Create a Pull Request (PR) from your branch to the main branch of this repository.

## 💬 Communication

- Be respectful and follow the [Code of Conduct](CODE_OF_CONDUCT.md).
- All code, comments, variable names, function names, and identifiers **must be written in English**.
- English is also the required language for all contributions, discussions, commit messages, and pull requests.
- Avoid using abbreviations or words from other languages in code unless they are established technical terms.

## 🖋️ Code style and formatting

- Follow existing code style and conventions.
- Write clean and understandable code.
- Add comments if needed.

### 📐 Code and naming conventions

- Constants has uppercase names. Name prefix is divided by underscore (_). 
  - Long name constants starts with one uppercase letter after underscore, then small letters and next word of name starts with uppercase letter and continues with small ones. 
  - Constants with simple value are one on one row.
  - Constants with sets are written on one line with name, assignment, set start. Each one value is on separated line, last separated line is without value and signs end of set.
- Function usually starts with lowercase and each word in name starts with uppercase and continue lowercase. 
- Argument name should start with lowercase and each word in name starts with uppercase and continue lowercase.

```javascript
const STO_DATA = 'STO_DATA';
const CFG_KEY_OverrideSidebarVisible = 'OverrideSidebarVisible';

// constants with sets are written this way:
var variable1 = {
  'KEY' : () => `Text`,
  'KEY2' : () => `Text2`,
};

function configGetValue(key, backup, CFG = FILE_CONFIG) {
//...
}
```

### 🚫 Restrictions

- No custom elements (web components)
- No JS modules, or frameworks like React/Vue/jQuery

## ✅ Testing

- Test your changes manually as automated tests are not currently available.

## 🔍 Review and approval

- PRs will be reviewed before merging.
- Please be patient during the review process.

## 📦 Versioning

- Versions use YYYYMMDD format; multiple releases per day get suffixes like -1, -2
- The project leadership manages releases and changelogs.
- Your changes may be part of a broader logic, so there may be needed to test the overall functionality before releasing
- Please be patient while waiting for the actual public release of your changes

## 🎯 Roles and project management

- Major decisions are made by project leadership.
- Contact leadership for deeper involvement.

Thank you for your time and effort! 🙌
