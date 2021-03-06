# Papers

## 1. [Image Processing for Artist Identification](http://web.math.princeton.edu/ipai/spm.pdf)

### Pros

* Leave-one-out cross validation
* High-res images
* Positive results (2 false positives, 2 false negatives)
* Manage to detect brushtrokes despite grayscale

### Cons

* Very few negative examples (6)
* High-res images only grayscale
* No ground truth for brush strokes?
* Penn State requires a priori knowledge
* Paintings excluded from Princetown due to darkness of colours
* Single artist focus (with forgeries)

### General Points

* Grayscale makes brushstroke detection difficult
* Potential analysis using fluid dynamics


## 2. [Rhythmic Brushstrokes Distinguish van Gogh from His Contemporaries: Findings via Automated Brushstroke Extraction](http://infolab.stanford.edu/~wangz/project/imsearch/ART/PAMI11/li.pdf)

### Pros

* Close work with art historians
* Promising results

### Cons

* Focuses on a single artist -> very specific
* No ground truth for brush strokes

## 3. [An Investigation of Multispectral Imaging for the Mapping of Pigments in Paintings](http://www.art-si.org/PDFs/Processing/PigmentMapping-Zhao2007.pdf)

### Pros

* Account for the system of capturing images
* Multispectral imaging used in other fields sucessfully
* Potentially very powerful analysis technique to work out pigments

### Cons

* Some priori knowledge input into the system (VG known not to use black paint)
* More about recovery of originals than analysing images
* No automatic detection of pigment maps (?)
* Requires more hardware than software

## 4. [A Digital Technique for Art Authentication](http://www.cs.dartmouth.edu/~rockmore/pnas-rev.pdf)

### Pros

* High-res images
* Promising results
* Results correspond with expert

### Cons

* Tiny data set (13 images)
* Results only expressed in terms of distance
* Specific to a small group of artists with a similar style

## 5. [When Van Gogh meets Mandelbrot: Multifractal classification of painting's texture](http://www.sciencedirect.com/science/article/pii/S0165168412000308)

### Pros

* Intensity, RGB and HSL
* Very interesting concepts and potentially very useful (?)

### Cons

* Manual selection of patches requires expert knowledge and cannot be automated
* Bindly patched
* Discrimination of soft brush difficult
* Sensitive to canvas structure
* Sensitive to low-res images
* Small data set

## 6. [Image Fusion for Difference Visualization in Art Analysis](http://library.utia.cas.cz/separaty/2013/ZOI/blazek-0398593.pdf)

### Pros

* Identification of Regions of Interest faster and more precise (no results to back this up)
* Can be applied to multiple images

### Cons

* Visualisation rather than analysis
* Single colour space
* Only really applicable to similar images
* Re-use of an existing colour space to show something different

## 7. [Analysis of The Distributions of Colour Characteristics in Art Painting Images](http://paws.kettering.edu/~pstanche/SJC052%20(3).pdf)

### Pros

* Good number of artists and periods
* Lightweight
* Working system
* Large overall data set

### Cons

* Built on a lot of existing research
* Fairly basic information considered
* Small data set per artist
* No expert backup (?)


## 8. [Histograms of oriented gradients for human detection](http://ieeexplore.ieee.org/xpl/login.jsp?tp=&arnumber=1467360&url=http%3A%2F%2Fieeexplore.ieee.org%2Fxpls%2Fabs_all.jsp%3Farnumber%3D1467360)

### Pros

* Positive results
* Simple yet effective histograms

### Cons

* Not directly intended for artwork
* Not all of the technique is useful for artwork


## 9. [Stylistic Analysis of Paintings using Wavelets and Machine Learning](http://web.math.princeton.edu/ipai/dating.pdf)

### Pros
### Cons


## 10. [The Van Gogh Project: Art Meets Mathematics in Ongoing International Study](http://www.siam.org/news/news.php?id=1568)

### Pros
### Cons


## 11. [Texton-Based Analysis of Paintings](http://repository.tudelft.nl/assets/uuid:fb3803a0-d8e1-432e-87cb-00e0c8e5a62e/7798Laurens.pdf)

### Pros
### Cons


## 12. [The Design and Use of Steerable Filters](http://people.csail.mit.edu/billf/papers/steerpaper91FreemanAdelson.pdf)

### Pros

* Textbook-like reference
* Illustrative and mathematical
* Theoretical and practical elements
* Even 3-D steerable filters

### Cons

* No proper results`

## 13. [Texture Discrimination by Gabor Functions](http://scil.dinf.usherbrooke.ca/wp-content/courses/imn764/misc/Turner_1990.pdf)

### Pros
### Cons


## 14. [Stroke Extraction for Chinese Calligraphy Characters](http://www.jofcis.com/publishedpapers/2012_8_6_2493_2500.pdf)

### Pros
### Cons


## 15. [Animating Chinese Paintings through Stroke-Based Decomposition](http://research.microsoft.com/en-us/um/people/sbkang/publications/tog06.pdf)

### Pros
### Cons


## 16. [Can we date an artist's work from catelogue photographs?](http://ieeexplore.ieee.org/xpl/articleDetails.jsp?tp=&arnumber=6703803)

*Because self-citation is win*

### Pros

* Novelty
* Good range of features
* Promising results
* Good possibility of continuing work
* Application of existing techniques to a real problem
* Exemplars

### Cons

* Basic features
* Low-res images
* No unification of lighting, etc.
* Painting size is actually the best indicator of time
