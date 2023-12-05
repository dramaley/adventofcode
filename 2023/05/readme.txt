The data set for part 2 includes 1,917,300,386 seeds. That's a lot. My first
solution is the one marked "naïve", as it just iterates through all of those and
checks each one. As one may imagine, performance of that solution was not great:
    $ time -p ./part2-naïve < input
    real 19318.61
    user 19305.73
    sys 3.91
    37806486
    $ 

While that was running, i worked on the better solution. It's a bit more
efficient:
    $ time -p ./part2 < input
    real 0.00
    user 0.00
    sys 0.00
    37806486
    $ 
