# Ninja
Ninja contains some common scripts in Linux system that can make your work more efficient


## Usage

 * git clone https://github.com/gaol/ninja

 * source the `common_source` from your `.bashrc`:

> `. ninja/common_source`

> NOTE: you can simply source it by specifying the file location when start the login bash:
<pre>
if [ -f $HOME/bin/common_source ]; then
	. $HOME/bin/common_source
fi
</pre>

That is All.

## Adding more scripts:

 * put any scripts(bash shell, python, ruby, etc) with execution permission in the `ninja` home directory or `scripts` sub directory, it has been added to the `$PATH` environment
 * for functional scripts, define them in the `ninja/scripts/function.d/`, they will be loaded once you source the `common_source` again.

Have Fun!
