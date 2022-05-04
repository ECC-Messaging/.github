# ECC Messaging

This is a project made to fulfill requirements for coursework.

### Objective

Our goal is to enable others to create smaller scale encrypted systems easily as an ECC scheme needs about 256 bits while an RSA scheme needs 3072 for 128 bits of security.

This package will enable developers to quickly implement a secure messaging scheme on a wide variety of systems without much thought, thereby increasing their productivity.

### Future Goals
 - Perform extensive tests to verify that hackers cannot get private key
 - Test that attackers cannot modify message in transit. Possible add hash check to verify this.
 - Allow users to login from anywhere and still have the same private key.
 - Improve the package so that it can handle more data types than just plain text, such as images or videos.


## Get Started

To get started head over to the main [repo](https://github.com/ECC-Messaging/ECC-Messaging) and clone the project. From there clone the submodules with the git command:

```git submodule update --init --recursive```

### Submodule: Frontend 

This is a [demo](https://ecc-messaging-demo.surge.sh/) on how one may use our NPM package. 
It is a very simple forum with basic login capabilities written in Svelte. We utilize simple JSON databases from [Pantry](https://getpantry.cloud) to create proper functionality.


### Submodule: Package 

This is the core product made. We have both a main version: which is written in [typescript](https://www.npmjs.com/package/ecc-messaging-scheme-package) as well as a branch written in [python](https://pypi.org/project/ecc-messaging-scheme-package/).
