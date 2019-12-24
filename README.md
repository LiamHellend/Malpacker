# Malpacker

## Description

Malpacker is a webservice that allows malware analysts to quickly detect and possibly automatically unpack, packed malware. The webservice primairly attempts to unpack malware into the original full binary, however it may only be possible partially unpack the malware, depending on how the malware was packed.

## Key features
* Allow malware to be uploaded
* Attempt to detect the use of packing
* Attempt to unpack the full binary
* Attempt to extract parts of the binary if full unpacking is not possible
* Allow the unpacked or partially unpacked binary to be downloaded

## Opensource unpackers in use
* https://github.com/unipacker/unipacker
* https://github.com/hasherezade/mal_unpack
* https://github.com/avast/retdec
* https://github.com/NozomiNetworks/greyenergy-unpacker
* https://github.com/quarkslab/legu_unpacker_2019