- Make `isLength() / isByteLength()` also accept `{min, max}` as options object.
  ([#474](https://github.com/chriso/validator.js/issues/474))

#### 4.5.0

- Add validation for Indian mobile phone numbers
  ([#471](https://github.com/chriso/validator.js/pull/471))
- Tweak Greek and Chinese mobile phone validation
  ([#467](https://github.com/chriso/validator.js/pull/467),
   [#468](https://github.com/chriso/validator.js/pull/468))
- Fixed a bug in `isDate()` when validating ISO 8601 dates without a timezone
  ([#472](https://github.com/chriso/validator.js/issues/472))

#### 4.4.1

- Allow triple hyphens in IDNA hostnames
  ([#466](https://github.com/chriso/validator.js/issues/466))

#### 4.4.0

- Added `isMACAddress()` validator
  ([#458](https://github.com/chriso/validator.js/pull/458))
- Added `isWhitelisted()` validator
  ([#462](https://github.com/chriso/validator.js/pull/462))
- Added a New Zealand locale to `isMobilePhone()`
  ([#452](https://github.com/chriso/validator.js/pull/452))
- Added options to control GMail address normalization
  ([#460](https://github.com/chriso/validator.js/pull/460))

#### 4.3.0

- Support Ember CLI module definitions
  ([#448](https://github.com/chriso/validator.js/pull/448))
- Added a Vietnam locale to `isMobilePhone()`
  ([#451](https://github.com/chriso/validator.js/pull/451))

#### 4.2.1

- Fix `isDate()` handling of RFC2822 timezones
  ([#447](https://github.com/chriso/validator.js/pull/447))

#### 4.2.0

- Fix `isDate()` handling of ISO8601 timezones
  ([#444](https://github.com/chriso/validator.js/pull/444))
- Fix the incorrect `isFloat('.') === true`
  ([#443](https://github.com/chriso/validator.js/pull/443))
- Added a Norwegian locale to `isMobilePhone()`
  ([#439](https://github.com/chriso/validator.js/pull/439))

#### 4.1.0

- General `isDate()` improvements
  ([#431](https://github.com/chriso/validator.js/pull/431))
- Tests now require node 4.0+
  ([#438](https://github.com/chriso/validator.js/pull/438))

#### 4.0.6

- Added a Taiwan locale to `isMobilePhone()`
  ([#432](https://github.com/chriso/validator.js/pull/432))
- Fixed a bug in `isBefore()` where it would return `null`
  ([#436](https://github.com/chriso/validator.js/pull/436))

#### 4.0.5

- Fixed a denial of service vulnerability in the `isEmail()` regex
  ([#152](https://github.com/chriso/validator.js/issues/152#issuecomment-131874928))

#### 4.0.4

- Reverted the leap year validation in `isDate()` as it introduced some regressions
  ([#422](https://github.com/chriso/validator.js/issues/422), [#423](https://github.com/chriso/validator.js/issues/423))

#### 4.0.3

- Added leap year validation to `isDate()`
  ([#418](https://github.com/chriso/validator.js/pull/418))

#### 4.0.2

- Fixed `isDecimal()` with an empty string
  ([#419](https://github.com/chriso/validator.js/issues/419))

#### 4.0.1

- Fixed `isByteLength()` with certain strings
  ([09f0c6d](https://github.com/chriso/validator.js/commit/09f0c6d2321f0c78af6a7de42e91b63955e4c01e))
- Put length restrictions on email parts
  ([#258](https://github.com/chriso/validator.js/issues/258#issuecomment-127173612))

#### 4.0.0

- Simplified the `isEmail()` regex and fixed some edge cases
  ([#258](https://github.com/chriso/validator.js/issues/258#issuecomment-127173612))
- Added ISO 8601 date validation via `isISO8601()`
  ([#373](https://github.com/chriso/validator.js/issues/373))
