# 221A
√ radical-tab

## usage
`⎈⇧u221a␣⭾`
<br>`⇧⎈u221a␣⭾`

## update
`cd ~/221A;git pull --all`

## installation
`cd ~;git clone https://github.com/radical-lab/221A.git;cat<<<'export PATH="$PATH:$HOME/221A"'>>~/.profile`

`~/.profile` is the most [portable](https://en.wikipedia.org/wiki/Unix_shell#Configuration_files)

## known bugs

### `√goto`
* catastrophic failure
	* fix: `. √goto $address`

### `√map` and `√apply` generalise `wc --files0-from=$F` and adheres to the [dotadiw](https://en.wikipedia.org/wiki/Unix_philosophy#Do_One_Thing_and_Do_It_Well) principle making `wc` seem `/(.|g)?nu/`
* ansi escaped syntax formatting
