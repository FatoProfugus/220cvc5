# 220cvc5
To test project install fresh Ubuntu 20 on a VM.<br/>

What to download after fresh Ubuntu install:

cmake<br/>
g++<br/>
python3-pip<br/>
python3 -m pip install toml<br/>
java<br/>
m4<br/>
Then follow instructions from cvc5 docs<br/>
<br/>

To build scripts after installing cvc5 clone this repo<br/>
and run make.<br/>

For some reason demorgans.cpp isn't working anymore so it was<br/>
removed from the Makefile all target. I think this is due to a<br/>
recent change to cvc5.<br/>

gates_cvc5 is the main executable that was used for benchmarking.<br/>

To replicate benchmarks run the following:<br/>
./gates_cvc5 test_chain10<br/>
./gates_cvc5 test_chain100<br/>
./gates_cvc5 test_chain1000<br/>
./gates_cvc5 test_chain10000<br/>
./gates_cvc5 test_tree10<br/>
./gates_cvc5 test_tree100<br/>
./gates_cvc5 test_tree1000<br/>
./gates_cvc5 test_tree10000<br/>
./gates_cvc5 test_mesh10<br/>
./gates_cvc5 test_mesh100<br/>
./gates_cvc5 test_mesh1000<br/>
./gates_cvc5 test_mesh10000<br/>
