#!/usr/bin/env perl

use strict;
use warnings;
use Data::Dumper;

use LWP::UserAgent;

my $url = "http://www.dover.jp/?mode=cate&cbid=2437947&csid=1";
my $ua = LWP::UserAgent->new();
my $res = $ua->get($url);

print Dumper $res;
