# ATM Service

Welcome to the ATM Service project, a simple command-line program developed by Pankaj Rawat. This program simulates an ATM machine, allowing users to check their balance, withdraw money, and deposit funds.

## Getting Started

To use this program, follow these steps:

1. Clone the repository to your local machine.

```bash
git clone https://github.com/awkwardpy/ATM.git
```

2. Compile the code using a C compiler. For example, you can use GCC to build the executable:

```bash
gcc ATM.c -o atm
```

3. Run the program:

```bash
./ATM
```

## Usage

Upon running the program, you'll be presented with the following options:

1. **Check Balance:** This option displays your current account balance.
2. **Withdraw Money:** Specify the amount to withdraw, and the program will provide you with the requested amount if you have sufficient funds.
3. **Deposit Money:** Specify the amount you want to deposit into your account.
4. **Exit:** Quit the ATM service.

## PIN and Card Number

By default, the ATM service uses a fixed PIN (1234) for demonstration purposes. You can modify the `atmPin` variable in the code to set your preferred PIN. Also, the program will prompt you to enter a debit card number. You can replace the default card number with your own if needed.

```c
int atmPin = 1234;
int card;
```

## Contributing

If you want to contribute to this project, please fork the repository and create a pull request with your changes. We welcome contributions and improvements to this simple ATM service.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

If you have any questions or suggestions, feel free to reach out to Pankaj Rawat at awkwardpy@email.com.

Enjoy using this simple ATM simulator!
