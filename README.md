# Unofficial PHP library for interacting with the Multichain JsonRPC interface

This library provides a simple way to work with Multichain JsonRPC interface. The entire API is implemented and the tests contain easy to follow examples on performing most of the operations. 

## Example usage

    $client = MultichainClient("http://<chainurl>:8000", 'multichainrpc', '79pgKQusiH3VDVpyzsM6e3kRz6gWNctAwgJvymG3iiuz', 3, false);
    $address = $client->setDebug(true)->getNewAddress();

See more examples and documentation in the tests folder.

## Installing libphp-multichain

The recommended way to install this library through Composer. Run the Composer command to install the latest stable version:

    composer require kunstmaan/libphp-multichain

## Need a development Blockchain and like Docker?

Take a look at [these Docker images](https://github.com/Kunstmaan/docker-multichain) we have built.