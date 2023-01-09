# AcousticVehicleDetection

This is the main branch for the paper titled "Improved Vehicle Sub-type Classification for
Acoustic Traffic Monitoring"

The IDMT-Traffic dataset can be found on the following link: https://www.idmt.fraunhofer.de/en/publications/datasets/traffic.html

Abstract—The detection and classification of vehicles on the
road is a crucial task for traffic monitoring. Usually, Computer
Vision (CV) algorithms dominate the task of vehicle classification
on the road, but CV methodologies might suffer in poor lighting
conditions and require greater amounts of computational power.
Additionally, there is a privacy concern with installing cameras in
sensitive and secure areas. In contrast, acoustic traffic monitoring
is cost-effective, and can provide greater accuracy, particularly
in low lighting conditions and in places where cameras cannot be
installed. In this paper, we consider the task of acoustic vehicle
sub-type classification, where we classify acoustic signals into 4
classes: car, truck, bike, and no vehicle, with a focus on the
harder task of distinguishing between car and truck samples.
We experimented with Mel spectrograms, MFCC and GFCC
as features and performed careful data pre-processing to train
a simple, well optimized CNN that performs well at the task.
When used with MFCC as features, our proposed methodology
improves upon the established state-of-the-art baseline in the
IDMT Traffic dataset with an accuracy of 98.95%.
