# DS160-Fill

DS160-Fill is a JavaScript script designed to speed up the completion of the DS160 form on the CEAC website (ceac.state.gov).

## Usage

Execute the script dynamically using the browser console.

- Press F12
- Paste the script provided below
- Press Enter

```javascript
eval(await (await fetch('https://raw.githubusercontent.com/felipeczpaz/DS160-Fill/main/script.js')).text());
```

Ensure the correctness of the URL (https://raw.githubusercontent.com/felipeczpaz/DS160-Fill/main/script.js) and always verify the script's content.

## Contributing

We welcome pull requests. For significant changes, kindly open an issue first to discuss proposed modifications.

Please ensure that you update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)
