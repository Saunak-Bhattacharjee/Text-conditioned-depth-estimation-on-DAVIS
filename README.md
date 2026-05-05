# Text-conditioned-depth-estimation-on-DAVIS
This is a github repository of a project that looks into a whether a vision model can be conditioned into understanding monocular depth in an image if it is supported with textual descriptions of the scene

##Motivation

Monocular depth estimation — predicting depth from a single RGB image — is fundamentally an underdetermined problem. There are infinitely many 3D scenes consistent with any 2D image. To resolve this ambiguity, models rely on learned priors about object shapes, perspective cues, and typical scene layouts.

The main question is whether a model already encodes a rich visual prior (via CLIP), can a *language prior* help further? Intuitively, knowing that an image contains "a cyclist in front of a graffiti wall" should help disambiguate depth, the cyclist is closer than the wall, and the wall is flat.

##Method


