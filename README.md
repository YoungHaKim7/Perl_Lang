# Perl_Lang

Perl Tutorial

https://youtu.be/WEghIXs8F6c

<br>

# Perl Install (macOS)

```
$ brew install perl
```

<br>

# Perl Language

https://www.perl.org/

<br>

# Terminal 창에서 실행하기

```
$ perl -e 'print "Hello World\n"'

Hello World
```

<hr>

# .pl 파일 만들어서 실행하기

- perllib.pl
  <br>

```
use strict;
use warnings;
use diagnostics;

use feature 'say';

use feature "switch";

use v5.16;

# Comment

print "Hello World\n";

my $name = 'GlobalYoung';

my ($age, $street) = (40, '123 Main St');

my $my_info = "$name lives on \"$street\"\n";

$my_info = qq{$name lives on "$street"\n};

print $my_info;

my $bunch_on_info = <<"END";
This is a
bunch of information
on multiple lines
END

say $bunch_on_info;

my $big_int = 181818181818119383287198;

# %c : Character
# %s : string
# %d : Decimal
# %u : Unsigned integer
# %f : Floating Point (Decimal Notation)
# %e : Floating Point (Scientific Notation)

printf("%u \n", $big_int + 1);


```

# Result

```
$ perl perllib.pl

Hello World
GlobalYoung lives on "123 Main St"
This is a
bunch of information
on multiple lines

18446744073709551615
```
