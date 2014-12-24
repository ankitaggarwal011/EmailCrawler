# Email crawler

This python code simply crawls the given web addresses for potentional emails and saves those in a text file. Web urls have to be specified in a text file seperated by newline.

## Motivation

This can be helpful script to automate the task of finding relevant email addresses provided one knows the associated web urls.

## Dependencies
The python modules are needed in order to use this library.
```
sys
urllib
```

## Usage
Clone the repository and use the following code.
Run the command directly from the console with command line arguments to the file emailcrawler.py. The command line arguments are explained as:

```
emailcrawler.py [filename]

```
For example,

```sh
$ python emailcrawler.py example.txt
```
example.txt contains newline separated web urls on which the email addresses are to be located and saved. This command saves three text files, namely, email_addresses.txt (containing email addresses found), email_addresses_withurl.txt (contains email addresses mapped with associated urls) and info.txt (general information on number of pages crawled and number od emails found).

## Contributors

#### Author: Ankit Aggarwal

## License

[MIT License](https://github.com/ankitaggarwal011/email-crawler/blob/master/LICENSE)
