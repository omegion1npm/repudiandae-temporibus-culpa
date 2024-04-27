[![npm](https://img.shields.io/npm/v/@omegion1npm/repudiandae-temporibus-culpa.svg)](https://www.npmjs.com/package/@omegion1npm/repudiandae-temporibus-culpa) ![downloads](https://img.shields.io/npm/dt/@omegion1npm/repudiandae-temporibus-culpa.svg) [![CI](https://github.com/omegion1npm/repudiandae-temporibus-culpa/actions/workflows/ci.yml/badge.svg)](https://github.com/omegion1npm/repudiandae-temporibus-culpa/actions)

# Is-Valid-ABN

Check if a number is a valid Australian Business Number (ABN).

## tl;dr

- Install by executing `npm install @omegion1npm/repudiandae-temporibus-culpa` or `yarn add @omegion1npm/repudiandae-temporibus-culpa`.
- Import by adding `import isValidABN from '@omegion1npm/repudiandae-temporibus-culpa'`.
- Use it by writing `const valid = isValidABN('83914571673')`

## See also

- [is-valid-acn](https://github.com/wojtekmaj/is-valid-acn): Check if a number is a valid Australian Company Number (ACN).

## Examples

```ts
isValidABN('83914571673'); // true

isValidABN('83 914 571 673'); / true

isValidABN('83-914-571-673'); // true
```

## License

The MIT License.

## Author

<table>
  <tr>
    <td >
      <img src="https://avatars.githubusercontent.com/u/5426427?v=4&s=128" width="64" height="64" alt="Wojciech Maj">
    </td>
    <td>
      <a href="https://github.com/wojtekmaj">Wojciech Maj</a>
    </td>
  </tr>
</table>
