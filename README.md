# Bitcoin price to Excel

A tool for downloading daily historical Bitcoin prices between two dates chosen by the user via the command line.
The API  is “Powered by [CoinDesk](https://www.coindesk.com/price/bitcoin)”.
Data is stored according to the dates chosen within the current working directory in the form. For example, if the START and END dates chosen are 2018/01/01 and 2019/01/01 respectively, the file will be named: 'bitcoin-hist2018-01-01-2019-01-01.xlsx'.



## Usage

```bash
python3 main.py

Start Year YYYY:  2018
Start Month MM:  01
Start Day DD:  01
End Year YYYY:  2019
End Month MM:  01
End Day DD:  01

Your file is saved as bitcoin-hist2018-01-01-2019-01-01.xlsx

```

## Contributing
Pull requests are welcome.

## License
[MIT](https://choosealicense.com/licenses/mit/)
