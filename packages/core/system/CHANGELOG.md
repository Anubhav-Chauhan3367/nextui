# @nextui-org/system

## 2.2.4

### Patch Changes

- Updated dependencies [[`5591138bf`](https://github.com/nextui-org/nextui/commit/5591138bff4a393f614c4cb0d505901560c4ceea)]:
  - @nextui-org/system-rsc@2.1.4

## 2.2.3

### Patch Changes

- [#3331](https://github.com/nextui-org/nextui/pull/3331) [`f5d94f96e`](https://github.com/nextui-org/nextui/commit/f5d94f96e4cffed1d4aeef971c89f8d283effd49) Thanks [@wingkwong](https://github.com/wingkwong)! - Fixed incorrect year in `showMonthAndYearPickers` with different locales

- Updated dependencies [[`0cdfdb48b`](https://github.com/nextui-org/nextui/commit/0cdfdb48bcb7eecb752fc6a3033d3bdd2335872b), [`f785d1fb0`](https://github.com/nextui-org/nextui/commit/f785d1fb0460df73912bcd6614bc78d46db14e6b)]:
  - @nextui-org/system-rsc@2.1.3
  - @nextui-org/react-utils@2.0.15

## 2.2.2

### Patch Changes

- [#3240](https://github.com/nextui-org/nextui/pull/3240) [`47c2472fb`](https://github.com/nextui-org/nextui/commit/47c2472fb22bfe1c0c357b5ba12e5606eba0d65b) Thanks [@wingkwong](https://github.com/wingkwong)! - bump react-aria dependencies

- Updated dependencies [[`b9bb06ff3`](https://github.com/nextui-org/nextui/commit/b9bb06ff37f99bfc438e848706ec79b4c7b7c5d3)]:
  - @nextui-org/react-utils@2.0.14
  - @nextui-org/system-rsc@2.1.2

## 2.2.1

### Patch Changes

- [#3119](https://github.com/nextui-org/nextui/pull/3119) [`685995a12`](https://github.com/nextui-org/nextui/commit/685995a125cc3db26c6adb67ed9f7245b87e792a) Thanks [@wingkwong](https://github.com/wingkwong)! - bump `@react-aria/utils` version to `3.24.1` and bump `@react-types/shared` to `3.23.1`

- [#3119](https://github.com/nextui-org/nextui/pull/3119) [`685995a12`](https://github.com/nextui-org/nextui/commit/685995a125cc3db26c6adb67ed9f7245b87e792a) Thanks [@wingkwong](https://github.com/wingkwong)! - Fixed listbox href issue (#3105)

- Updated dependencies []:
  - @nextui-org/system-rsc@2.1.2

## 2.2.0

### Minor Changes

- [#2987](https://github.com/nextui-org/nextui/pull/2987) [`540aa2124`](https://github.com/nextui-org/nextui/commit/540aa2124b45b65a40e73f5aea2b90405fe1fe9a) Thanks [@ryo-manba](https://github.com/ryo-manba)! - Change validationBehavior from native to aria by default, with the option to change via props.

### Patch Changes

- [#2915](https://github.com/nextui-org/nextui/pull/2915) [`e3afa4789`](https://github.com/nextui-org/nextui/commit/e3afa4789a1ac0fa929b2acaca5bd9c520567ab8) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - The `cn` utility was moved the `theme` package and updated to support NextUI custom classes.

- [#2929](https://github.com/nextui-org/nextui/pull/2929) [`422770cc6`](https://github.com/nextui-org/nextui/commit/422770cc6bcdd1d4c51257654ab718f3c19d6cb2) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - Add support for disabling the animations globally.

- Updated dependencies [[`e3afa4789`](https://github.com/nextui-org/nextui/commit/e3afa4789a1ac0fa929b2acaca5bd9c520567ab8), [`1109baea6`](https://github.com/nextui-org/nextui/commit/1109baea6ac6aa3feb2be90ef065f61b2c2a06a9)]:
  - @nextui-org/system-rsc@2.1.2

## 2.1.2

### Patch Changes

- [#2789](https://github.com/nextui-org/nextui/pull/2789) [`eccc2f2f3`](https://github.com/nextui-org/nextui/commit/eccc2f2f3d856eefb2cc7c07b94e1c4cefd4d7d0) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - Fix #2749 Introduced named exports for several UI-related packages to enhance modularity and usability in Next.js projects.

- Updated dependencies [[`eccc2f2f3`](https://github.com/nextui-org/nextui/commit/eccc2f2f3d856eefb2cc7c07b94e1c4cefd4d7d0)]:
  - @nextui-org/react-utils@2.0.13
  - @nextui-org/system-rsc@2.1.1

## 2.1.1

### Patch Changes

- [#2758](https://github.com/nextui-org/nextui/pull/2758) [`74eda3128`](https://github.com/nextui-org/nextui/commit/74eda312883b2e17df26f71442aba9fb3cd240be) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - Named exports for rsc packages, "use client;" directive added to "@nextui-org/react" package

- Updated dependencies [[`74eda3128`](https://github.com/nextui-org/nextui/commit/74eda312883b2e17df26f71442aba9fb3cd240be)]:
  - @nextui-org/system-rsc@2.1.1
  - @nextui-org/react-utils@2.0.12

## 2.1.0

### Minor Changes

- [#2618](https://github.com/nextui-org/nextui/pull/2618) [`dc0bcf13a`](https://github.com/nextui-org/nextui/commit/dc0bcf13a5e9aa0450938bcca47cd4c696066f14) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - v2.3.0

### Patch Changes

- [#2618](https://github.com/nextui-org/nextui/pull/2618) [`dc0bcf13a`](https://github.com/nextui-org/nextui/commit/dc0bcf13a5e9aa0450938bcca47cd4c696066f14) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - - Calendar component added
  - objectToDeps function applied all across components
  - `useMeasure` hook added
  - `useIntersectionObserver` hook added
  - `framer-transitions` renamed to `framer-utils`
  - `ResizablePanel` component added to `framer-utils`
  - `test-utils` updated
- Updated dependencies [[`dc0bcf13a`](https://github.com/nextui-org/nextui/commit/dc0bcf13a5e9aa0450938bcca47cd4c696066f14), [`dc0bcf13a`](https://github.com/nextui-org/nextui/commit/dc0bcf13a5e9aa0450938bcca47cd4c696066f14), [`c5049edfd`](https://github.com/nextui-org/nextui/commit/c5049edfde7edaee2081d70e581739be9dcae2f9)]:
  - @nextui-org/system-rsc@2.1.0
  - @nextui-org/react-utils@2.0.11

## 2.0.15

### Patch Changes

- Updated dependencies [[`a978687b0`](https://github.com/nextui-org/nextui/commit/a978687b0736d1e15943ef46628fc4fa0723ddc7)]:
  - @nextui-org/system-rsc@2.0.11

## 2.0.14

### Patch Changes

- Updated dependencies [[`6ecdc278a`](https://github.com/nextui-org/nextui/commit/6ecdc278aba927ee38a799679b8eb99cba99cab9)]:
  - @nextui-org/system-rsc@2.0.10

## 2.0.13

### Patch Changes

- Updated dependencies [[`44ed1056e`](https://github.com/nextui-org/nextui/commit/44ed1056e717c56633f60cf289f78e9c7b83b648)]:
  - @nextui-org/system-rsc@2.0.9

## 2.0.12

### Patch Changes

- Updated dependencies [[`38af48faf`](https://github.com/nextui-org/nextui/commit/38af48faf5b62d2f81f2402f3d83d78991eb46e0)]:
  - @nextui-org/system-rsc@2.0.8

## 2.0.11

### Patch Changes

- [`25e86fb41`](https://github.com/nextui-org/nextui/commit/25e86fb41770d3cdae6dfdb79306b78fa02d8187) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - New version v2.2.0

- Updated dependencies [[`25e86fb41`](https://github.com/nextui-org/nextui/commit/25e86fb41770d3cdae6dfdb79306b78fa02d8187)]:
  - @nextui-org/system-rsc@2.0.7

## 2.0.10

### Patch Changes

- Updated dependencies [[`f6531c5f6`](https://github.com/nextui-org/nextui/commit/f6531c5f603d7f6308a597962ec6fab62c92fa93)]:
  - @nextui-org/system-rsc@2.0.6

## 2.0.9

### Patch Changes

- [#1600](https://github.com/nextui-org/nextui/pull/1600) [`b1b30b797`](https://github.com/nextui-org/nextui/commit/b1b30b7976f1d6652808fbf12ffde044f0861572) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - Fix npm deploy

- Updated dependencies [[`b1b30b797`](https://github.com/nextui-org/nextui/commit/b1b30b7976f1d6652808fbf12ffde044f0861572)]:
  - @nextui-org/system-rsc@2.0.5

## 2.0.8

### Patch Changes

- [#1589](https://github.com/nextui-org/nextui/pull/1589) [`1612532ee`](https://github.com/nextui-org/nextui/commit/1612532eeeabbc49165546b1a2e7aebf89e7a1c2) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - React aria packages upgraded

- Updated dependencies []:
  - @nextui-org/system-rsc@2.0.4

## 2.0.7

### Patch Changes

- Updated dependencies [[`d61428d9e`](https://github.com/nextui-org/nextui/commit/d61428d9e6c1c0590593fb1f0136e226051b7e23)]:
  - @nextui-org/system-rsc@2.0.4

## 2.0.6

### Patch Changes

- [#1513](https://github.com/nextui-org/nextui/pull/1513) [`641bf0885`](https://github.com/nextui-org/nextui/commit/641bf0885b6af2d7f36f27d83716a441975a5ca5) Thanks [@tianenpang](https://github.com/tianenpang)! - Extend props for NextUIProvider and update default locale from en to en-US.

- Updated dependencies []:
  - @nextui-org/system-rsc@2.0.3

## 2.0.5

### Patch Changes

- [#1359](https://github.com/nextui-org/nextui/pull/1359) [`a30cec48`](https://github.com/nextui-org/nextui/commit/a30cec4810988fb1962f3a61e0fc0362de08b171) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - \n

  - react-aria packages upgraded to the latest version
  - image storybooks fixed
  - other bug fixes..

## 2.0.4

### Patch Changes

- [#1350](https://github.com/nextui-org/nextui/pull/1350) [`710395f3`](https://github.com/nextui-org/nextui/commit/710395f3a2ca44238332237a49e948c933abe63d) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - Needless exports removed from system pkg

## 2.0.3

### Patch Changes

- [#1289](https://github.com/nextui-org/nextui/pull/1289) [`eefda8d6`](https://github.com/nextui-org/nextui/commit/eefda8d6e2088526e0dbb2026d807b53d2a97782) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - - "use client" directive removed from components that didn't need it

  - packages adapted to support RSC imports
  - filterDomProps function was modified to enable/disabled it

- [`e3e13a09`](https://github.com/nextui-org/nextui/commit/e3e13a095f2347ff279c85e6a5d3798f36c6533f) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - New package created to exports system RSC-compatible functions
  Component exports changed to named exports
- Updated dependencies [[`e3e13a09`](https://github.com/nextui-org/nextui/commit/e3e13a095f2347ff279c85e6a5d3798f36c6533f)]:
  - @nextui-org/system-rsc@2.0.3

## 2.0.2

### Patch Changes

- Updated dependencies [[`459ac5ed`](https://github.com/nextui-org/nextui/commit/459ac5ed4537942517803ba14129226a791d6feb)]:
  - @nextui-org/theme@2.0.2

## 2.0.1

### Patch Changes

- [`e940ec06`](https://github.com/nextui-org/nextui/commit/e940ec06ac5e46340d5956fb7c455a6ab3de3140) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - Introducing NextUI v2.0

- [`e940ec06`](https://github.com/nextui-org/nextui/commit/e940ec06ac5e46340d5956fb7c455a6ab3de3140) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - Introducing v2 - Readmes updated

- Updated dependencies [[`e940ec06`](https://github.com/nextui-org/nextui/commit/e940ec06ac5e46340d5956fb7c455a6ab3de3140), [`e940ec06`](https://github.com/nextui-org/nextui/commit/e940ec06ac5e46340d5956fb7c455a6ab3de3140)]:
  - @nextui-org/theme@2.0.1
