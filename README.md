# cseconvert

cseconvert is a cross platform Python utility script that extracts/converts SamacSys Library Loader/Component Search Engine files for use in PCB editor software.

## Requirements

* Python 2.7
* 'requests' package
* Internet access to https://componentsearchengine.com/
* A Component Search Engine account (free to register at https://componentsearchengine.com/register)

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install requests if not already installed

```sh
pip install requests
```

Make executable
```sh
chmod a+rx cseconvert
```

Move to your bin folder (method varies by operating system) (optional)
```sh
sudo mv cseconvert /usr/local/bin
```

## Usage

Extract to the current directory
```sh
cseconvert input_zip_file.zip
```

Extract to a specified directory
```sh
cseconvert input_zip_file.zip ~/Users/jacoblukewood/target_directory
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)