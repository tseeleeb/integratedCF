<<<<<<< HEAD
# integratedCF
=======
# integratedCF


ReadMe

Table of Contents
    •    Introduction
    •    Folder structure
    •    Key configurations to run the code for making experiments


Introduction
This code uses Surprise Framework which is a Python scikit for building and analyzing recommender systems that deal with explicit rating data.

This code implements:
    1.    User based CFs including UFC (baseline method directly from Surprise), UDemCF that incorporates demographic data
    2.    Item based CFs including IFC (baseline method directly from Surprise), ISemCF that incorporates semantic data

Folder structure
There are three folders as follows:

    IntegratedCFs
         ———> CredML1M
        ———> CredML100k
        ———> Experiment

CredML1M contains codes for the MovieLens 1M dataset, while CredML100k contains codes for the MovieLens 100K dataset. Each dataset has a different structure and way of organizing data, so they are separated into separate folders. However, the code is essentially the same for both.
