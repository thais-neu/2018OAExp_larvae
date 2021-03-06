# Remaining DNA methylation lab work - Aug 3 2020

[Link to presentation](https://docs.google.com/presentation/d/1IQWAnoi1YssHaI2vJz7E7c1psV4i2_fIw1D0lVJkgSI/edit#slide=id.g912977024d_0_19)

## Done

1) Sample extraction:
All samples (adult mantle, larvae, zygotes) have been extracted. 

Tables showing which samples we have viable DNA for either larvae or zygotes. 

**Zygotes**
![](https://github.com/epigeneticstoocean/2018OAExp_larvae/blob/master/notebook/img/ValidZygoteExtraction.png)

**Larvae**
![](https://github.com/epigeneticstoocean/2018OAExp_larvae/blob/master/notebook/img/ValidLarvaeExtraction.png)


This means there will be :
* 16 females (8 controls + 8 exposed)
* 15 zygtoes (8 control + 7 exposed)
* 22 larvae samples (9 control + 13 exposed)
* Total : 53 samples

The plan is to do WGBS on these samples, using a single lane of S4 2x150bp NovaSeq. 

This will give us > 25x coverage for all samples even with 10x duplication error (which is what i saw with the last oyster methylation data):
[calculation](https://github.com/epigeneticstoocean/2018OAExp_larvae/blob/master/notebook/20191112_illuminaCostCalSummary.md)

2) Test Bisulfite conversion
  
  * Confirmed that we can successfully prep libraries using pico methlyation kit and 100ng of larvae sample.

### TO-DO

3) Library prep 

**Plan** Lib. prep using duel index design with previously designed index (confirmed with genewiz this shouldn't be a problem). I will do BS conversion / library prep on all 53 samples. 

* Use 1% unmethylated lambda phage DNA in each library sample prep (i.e. 1ng lambda for 100ng sample)

Using adapters we have I can do a unique combinatorial index design, this should help with the [index hopping issue](https://support.illumina.com/bulletins/2017/08/recommended-strategies-for-unique-dual-index-designs.html)

[Additional info here](https://www.illumina.com/content/dam/illumina-marketing/documents/products/whitepapers/index-hopping-white-paper-770-2017-004.pdf)

### Timeline

I plan on processing samples in groups of ten (this makes sense since pico methylation kit has digestion tube aliquots also in batches of 10 samples). I budget 3 days per batch of ten, including library quantification at the end. This will mean 15 days to process 50 samples plus another 3 days (total of 18 days) to finish the remaining 3 samples and any samples that may have failed during the initial library prep. Working 6 days a week this should be done within 3 weeks. Tentative start date: Aug 24th.
