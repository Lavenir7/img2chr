# img2chr

![python3.10.9](https://img.shields.io/badge/python-3.10.9-yellow.svg?style=plastic)

## Introduction

A program that prints images as characters. (by python3)

> This project only contain a single file.

## Screenshot
![normal](./screenshot/normal.png)
![withparms](./screenshot/withparms.png)

## Dependencies

- python3-package: `pillow`

```sh
$ sudo pip install pillow
```

- (optional) linux command: `tput`

> `img2chr` uses `tput` to control the print width.
> 
> You can also manually control the print width using the `-x` option.

    - install `tput` on `termux`

    ```sh
    $ pkg install ncurses-utils
    ```

## Install

- Clone this repositories to your local.

```sh
$ git clone https://github.com/Lavenir7/img2chr
```

- Or just download the script file.

```sh
curl -sSL https://github.com/Lavenir7/img2chr/raw/refs/heads/master/script/img2chr
```

## Usage

- normal

show image:
```sh
$ img2chr example.jpg
```

- with parameters

print the image with `+` (`-x "+"`) at the widest width of `25` (`-w 25`)
```sh
$ img2chr -w 25 -x "+" example.jpg
```
> you can view descriptions of other parameters by `img2chr -h`

## End

Welcome to submit bugs in issues!

