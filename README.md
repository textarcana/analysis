# flat file mapreduce by whatever means are deemed expedient

## Installation

You can run these shell scripts from anywhere. But you will need to
install some Perl modules first:

    sudo cpan JSON Statistics::Basic Lingua::Any::Numbers

## How to run the tests

    bin/average tests/data/series/integer/sequential.txt

    bin/commafy 10101010110

    bin/humanize 10101010110

    bin/median tests/data/series/integer/sequential.txt

    bin/reduce tests/data/collections/tabular.txt

    bin/sum tests/data/series/integer/sequential.txt
