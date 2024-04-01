# Efficient-Fingerprint-Matching-and-Analysis-using-FLANN-and-Feature-Extraction

Fingerprints have been used as a personal identification tool for a long time because of their
uniqueness and time invariance. A fingerprint comprises ridges and valleys that correspond to the
dark and white areas in the gray-level image. Figure below shows the structure of a fingerprint which
includes examples of a crossover, core, bifurcation, ridge ending, island, delta and pore.

The most widely used fingerprint matching method is the minutiae-based matcher. The matcher
performs fairly accurate fingerprint matching for minutiae-based verification systems. However, the
system has a number of disadvantages. Firstly, a minutia shape, which is a ridge shape associated
with a minutia, can be cut off by cuts or scratches. The small cuts or scratches can be recovered by
the methods used in previous research such as a Gabor-filter. However, it is very difficult to recover
the ridges of a dry fingerprint which has lots of cuts. This can increase the ambiguity of minutiae
when ridge shapes are used. Secondly, the performance of this system will degrade significantly if
the overlapping area between the template and the input fingerprint image is small, and when the
number of available minutiae is few. This case occurs when a large translation of finger position
occurs or when a swipe sensor with a very narrow width is used. This paper proposes a new
fingerprint verification algorithm using SIFT-based minutiae descriptor (SMD). The proposed
method can successfully solve the two challenges mentioned above.

The proposed technique uses key points of SIFT for fingerprint verification. The proposed algorithm
has several advantages over previous SIFT-based methods. Firstly, the proposed approach utilizes proper image processing to make the SIFT feature extraction robust against variations attributable to
different finger pressures and noises. Secondly, the SIFT matcher is optimized for fingerprint
verification based on a Hough Transform to expand the fingerprint images into large rotation cases.
Thirdly, in order to enable the recognition system to perform in real time, a two-step fast matcher is
proposed.


# Dataset Link
https://www.kaggle.com/code/kairess/fingerprint-recognition/input
