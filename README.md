# aftermarket
aftermarket.pl  - bot scenario based on botreck to login make a screnshoot, get a list of domains, invoices 


scenarios for botreck: got aftermarket.pl , login,get history, get domains, ..

### Add to file: apifork.txt

https://github.com/botreck/aftermarket aftermarket

```bash
echo "https://github.com/botreck/aftermarket aftermarket" >> apifork.txt
```

and install in project

```bash
./apifork install
```

start using

```bash
./apidsl 'puppeteer.csv("aftermarket.pl/login_user_screenshot.csv")'
```