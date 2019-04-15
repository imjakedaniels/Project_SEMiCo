# SEMiCo

*For educational purposes.*

*Currently violates Twitters automation laws to auto-tweet using trends.*

### Randomly sampled text talking about corresponding image
```
tweet(text = sample(paste(seq1,local_trends[i,]$trend,paste0("is trending",marks), seq2),1), 
      mediaPath = paste0("~/semico/", local_trends[i,]$trend, ".png"))
```

Example:

"Whoa man, Donald Trump is trending... Seems like they mention emails the most" 

or
    
"pretty stupid Donald Trump is trending!? don't people have better things to do with their time?"


Goals:
* Will drop the explicit trend and use popular words in the tweet generation to comply
* Working on gathering more random colour generation for charts
* Adding phrases and puctuation variations to the tweet generator to make it seem more realistic
* To differentiate graph structure to bring another randomized element
* No Twitter API confirmation
* Will post some examples
