# geaux

## 1 WHY?

* We must never overlook the politics of everyday life, what people do together everyday at their essential retailer matters.  As this next great experiment in finance comes, corner stores and small grocers need to prepare for a long-term shift in how money and checkout works.  Our code runs on the idea that "_people don't want to make payments, they want to do what a payment facilitates_".  Shoppers want choice.  Sometimes they will want autonomous checkout and sometimes they will want to checkout with a cashier.  That in mind, we create a digital currency that lets shoppers deposit funds directly with their corner store or small grocer for autonomous checkout services, etc.  

* Imagine walking into your neighborhood essential retailer, "checking in", browsing, shopping and walking out. Our moonshot is to _normalize the idea of corner stores providing digital currency for autonomous checkout directly to guests with a simple swipe._  By pulling transactions out of the banking system we cut operating expenses for the essential retailer, which amount to 1-3% per transaction.  This credits system means transactions could be settled instantly on in-house digital ledgers, rather than the pipes of cards networks and banks. This approach also ensures corner store and small grocer payment infrastructure has a back-up system in the event power outages or cyber-attacks cause traditional payment channels to fail.  What's more, our autonomous checkout systems automates the dull and repetitive tasks of scanning goods making essential retail cashiers more productive in the sense they can focus more on things that create loyal regulars.

## 2 RESEARCH GOALS

* As with any AI learning, the syllabus determines the outcome.  We build our AI system to think like an ethnographer, very sensitive to the members meaning filling each respective space.  The code asks questions such as:  who benefits and who is harmed by this application?  And does it put power into the hands of the already powerful?  This approach to software ensures diversity and sustainability is built right into the system from the start. 
* Additionally, my goal is to showcase my ability to write software on embedded devices and design products competently at the graduate school level, even with my lack of per-requisite coursework.

## 3 INSPIRED BY BIOLOGY

* Inspired by the human visual cortex, our system contains two pathways the ventral - focused on the shape and color of objects and dorsal - tuned to the motion of objects. This approach two-stream helps us better understand how to model spatio-temporal cues at different scales across multiple cameras. 

## 4 CORNER STORE v-1 DATASET

ACTIONS / OBJECTS TRACKED
  * Store Items
  * Single Handed Pulls of Items From Shelf
  * Double Handed Pulls of Items From Shelf
  * Hand Offs of Items Between People
  * Non Shelf Pulls of Items
  * Tosses of Items Between People
  * Misplaced Items 
  * Final Item Inventory and Checkout
  * This dataset is a growing list.  It is mainly focused on scenarios that require long range temporal reasoning for differentiation.  Other scenarios focus more on the object-action relationship, such as people pulling itmes from a shelf. This current dataset has 100 action-object classes, with 100 clips for each action and each clip running approx 10 seconds. In total the v1 dataset has 10,000 videos. It should be noted that all clips collected have variable resolution and frame rates.

## 4 "PRETRAINING"

* We use an offshoot of ImageNet model to pre-train our computer vision system. We are immensely grateful for ImageNet and the human labor it took to sort, label and prep the millions of images across thousands of categories. Pre-training helps us avoid representational bottlenecks, boost our activations per tile and better balance the width and depth of the network.

## 5 ADDRESSING DATA BIAS

## 6 ANALYSIS, DESIGN & IMPLEMENTATION 

## 7 TRAINING DETAILS

* Learning Rates 
* Additional Data Prep
* Testing

## 8 EXPERIMENTS

* In this section we explore the accuracy and generalization of models on different benchmark data sets. 
* Accuracy = Repeatability + Calibration

## 9 RESULTS

## 10 MEASURING ACCURACY ACROSS BENCHMARK DATASETS

* UCF-101 DATASET - 13320 videos across 101 action classes
* Accuracy:
* HMDB-51 DATASET - 6766 videos across 51 action classes
* Accuracy:

## 11 DISCUSSION

## APPENDIX A: "CORNER STORE v-1" EXPANDED

## ACKNOWLEDGEMENTS

* This work was supported by my immediate family, close friends, confidants, my neighborhood grocers/corner stores and the open source community. 

## SANDBOX

* Teaching computer vision systems NOT to use guest biometrics as a condition of accepting payment under the Song Beverley Act of 1971
* Determining the metrics that improve downstream performance
* Better understanding the front-back orientation of human limbs due to clothing, lighting, background, optical interference
* "What You Almost Bought" Merchant Facing Application
* Bridging the edge-cloud barrier to lower server costs?
* Rewriting code and making arrays more ergonomic
* Lowering the costs of switching data across different corner stores
* Better understanding how social, economic and legal systems work together to achieve goals

## REFERENCES

* Writing Ethnographic Field Notes, 2nd Edition (2011)
* The Great Good Place by Roy Oldenburg (1989)
* 
* C++ for Business Programmers
* Building Business Applications Using C++
* Open Source Computer Vision for Beginnners: Learn OpenCv using C++ (2017)
* Learning OpenCV 3: Computer Vision in C++ with the OpenCV Library (2017)
*
* "Quo Vadis, Action Recognition? A New Model and the Kinetics Dataset" (2018)
* "Two-Stream Convolutional Networks for Action Recognition in Videos" (2014)
* "FlowNet 2.0: Evolution of Optical Flow Estimation with Deep Networks" (2016)
* "Spatiotemporal Residual Networks for Video Action Recognition" (2016)
* "Deep Residual Learning for Image Recognition" (2015)
* "Towards Good Practices for Very Deep Two-Stream ConvNets" (2015)
* "Temporal Segment Networks: Towards Good Practices for Deep Action Recognition" (2016)
