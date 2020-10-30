# genekeys-dataset
Provides a dataset with Genekey Keywords, which are triplicity correspondences to each of the I Ching Hexagrams (Shadow - Gift - Siddhi)

## Usage

~~~
import Genekeys from '../genekeys-dataset/genekeys';

// Get Shadow, Gift, Siddhi from 26th Hexagram
const ix = 26;
const { shadow, gift, siddhi } = Genekeys.find(x => x.hex === ix);
console.log(shadow, gift, siddhi);
~~~