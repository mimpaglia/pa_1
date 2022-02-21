
# README

Impaglia 2/20/2022

``` r
dur_hablo_stressed <- 602.998  
dur_hablo_unstressed <- 575.998  
dur_o_stressed <- 214.574  
dur_o_unstressed <- 218.317  
int_o_stressed <- 68.350  
int_o_unstressed <- 62.623  
f0_o_stressed <- 235.878  
f0_o_unstressed <- 244.920   
```

``` r
dur_hablo_stressed - dur_hablo_unstressed  
```

    ## [1] 27

``` r
dur_o_unstressed - dur_o_stressed  
```

    ## [1] 3.743

``` r
int_o_stressed - int_o_unstressed  
```

    ## [1] 5.727

``` r
f0_o_unstressed - f0_o_stressed  
```

    ## [1] 9.042

``` r
dif_hablo <-dur_hablo_stressed - dur_hablo_unstressed  
dif_o <- dur_o_unstressed - dur_o_stressed  
dif_int <- int_o_stressed - int_o_unstressed  
dif_f0 <- f0_o_unstressed - f0_o_stressed  
```

The duration of habló is 27 ms longer than hablo.  
The duration of the unstressed /o/ is 3.743 ms longer than the stressed
/o/.  
The intensity of the midpoint of the stressed /o/ is 5.727 db greater
than the intensity of the midpoint of the unstressed /o/.  
The pitch of the midpoint of the unstressed /o/ is 9.042 Hz greater than
the pitch of the midpoint of the stressed /o/.

## Conclusion

From listening to the two words hablo and habló, it sounded to me that
the duration of hablo is longer but this assumption was incorrect. As
expected, the duration of the unstressed /o/ is slightly longer than the
stressed /o/. It is also shown that while the intensity of the of the
unstressed /o/ is greater than the stressed /o/, the pitch of the
stressed /o/ is greater than the unstressed. Further investigation
needed to see if pitch and intensity are related to stress put on a
specific vowel.
