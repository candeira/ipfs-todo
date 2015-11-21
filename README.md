##  IPFS-TODO

This is my public commitment to work on IPFS.

If you think I should be working on something else, please send me a Pull Request!

- [ ] Elixir Multihashing on top of zabirauf/ex_multihash
    - [ ] Write README in the zabirauf style, with API from Erlang Crypto and js/go Multihash
    - [ ] Get test data from Go/JS, write tests
    - [ ] Write Multihashing and Multihashing.Crypto to the above tests.
    - [ ] Add hash truncation to zabirauf/ex_multihash, make PR
- [ ] Python Multihash/multihashing from JulienPalard's and tehmaze's
    - [ ] Write README describing API starting with this comment: https://github.com/ipfs/py-ipfs/issues/23#issuecomment-158641195
    - [ ] Rewrite JulienPalard's as multihashing to use tehmaze's multihash, use above comment for doctests
    - [ ] Add doctests to multihash too, unify style with multihashing
    - [ ] Write multihashing.hashlib as a subset of multihashing.multihashing 
- [ ] Add hash truncation to jbenet/multihash spec (it's in the go impl, and justified in issue comments, but not in spec)
- [ ] Review https://github.com/amstocker/python-multiaddr
- [ ] Lurk on lib2p2 conference hangout
- [ ] Find @amstocker on IRC and discuss multihash/multiaddr, and further plans.
