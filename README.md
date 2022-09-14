# web3.py-linux


linux 自带 python3，但是没有带pip，安装pip，sudo apt install python3-pip

安装之后，pip 和 pip3 都可以使用了

king@king-TM1701:~/文档/play_web3/py_version$ python3 -m pip -V
pip 22.0.2 from /usr/lib/python3/dist-packages/pip (python 3.10)

king@king-TM1701:~/文档/play_web3/py_version$ pip -V
pip 22.0.2 from /usr/lib/python3/dist-packages/pip (python 3.10)

king@king-TM1701:~/文档/play_web3/py_version$ pip3 -V
pip 22.0.2 from /usr/lib/python3/dist-packages/pip (python 3.10)

执行：python3 -m pip install web3


Installing collected packages: varint, netaddr, lru-dict, bitarray, websockets, toolz, pyrsistent, pycryptodome, parsimonious, multidict, hexbytes, frozenlist, eth-typing, eth-hash, charset-normalizer, base58, attrs, async-timeout, yarl, multiaddr, jsonschema, cytoolz, aiosignal, ipfshttpclient, eth-utils, aiohttp, rlp, eth-keys, eth-abi, eth-rlp, eth-keyfile, eth-account, web3
  WARNING: The script netaddr is installed in '/home/king/.local/bin' which is not on PATH.
  Consider adding this directory to PATH or, if you prefer to suppress this warning, use --no-warn-script-location.
  WARNING: The script normalizer is installed in '/home/king/.local/bin' which is not on PATH.
  Consider adding this directory to PATH or, if you prefer to suppress this warning, use --no-warn-script-location.
  WARNING: The script base58 is installed in '/home/king/.local/bin' which is not on PATH.
  Consider adding this directory to PATH or, if you prefer to suppress this warning, use --no-warn-script-location.
  WARNING: The script jsonschema is installed in '/home/king/.local/bin' which is not on PATH.
  Consider adding this directory to PATH or, if you prefer to suppress this warning, use --no-warn-script-location.
Successfully installed aiohttp-3.8.1 aiosignal-1.2.0 async-timeout-4.0.2 attrs-22.1.0 base58-2.1.1 bitarray-2.6.0 charset-normalizer-2.1.1 cytoolz-0.12.0 eth-abi-2.2.0 eth-account-0.5.9 eth-hash-0.5.0 eth-keyfile-0.5.1 eth-keys-0.3.4 eth-rlp-0.2.1 eth-typing-2.3.0 eth-utils-1.9.5 frozenlist-1.3.1 hexbytes-0.3.0 ipfshttpclient-0.8.0a2 jsonschema-4.16.0 lru-dict-1.1.8 multiaddr-0.0.9 multidict-6.0.2 netaddr-0.8.0 parsimonious-0.8.1 pycryptodome-3.15.0 pyrsistent-0.18.1 rlp-2.0.1 toolz-0.12.0 varint-1.0.2 web3-5.30.0 websockets-9.1 yarl-1.8.1
