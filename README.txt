This repo manages a file listing arbitration requests.

It is expected that the key responsible for signing these requests will be on (or attached to) an offline computer. 

The current version of the repo should be transferred to that computer using write-once media like CD-ROM. The offline signing process will then output a transaction in the form of a QR Code which can be scanned with a (normal, insecure) mobile phone and copied into https://etherscan.io/pushTX

It should also be manually checked before signing in case this repo or the PC used to transfer it was compromised.

Each line of the request file should contain a question ID, the correct answer and the account that should be credited with the correct answer. This will be the last user to post it, if the previous final answer was correct, or the account that requested arbitration, if the final answer was wrong.
