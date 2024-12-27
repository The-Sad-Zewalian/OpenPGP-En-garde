# OpenPGP-En-garde

This is the implementation of the attack done in the [paper](https://www.google.com/url?q=https://eprint.iacr.org/2005/033.pdf&sa=D&source=apps-viewer-frontend&ust=1687272087037043&usg=AOvVaw38aELof2Ja1qWcJcz144Jz&hl=en) by Serge Mister & Robert Zuccherato.

Please note that the original paper had a mistake in the general case when the attacker knows the first two bytes of some message block.
Refer to the corrected version of the paper in the following [book](https://link.springer.com/chapter/10.1007/11693383_4) page 87

## Requirements
The project requires Python 3.5 or later and the following libraries:

- Sandra 
- pycrypto
- pandas
