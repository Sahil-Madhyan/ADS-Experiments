# ADS EXP5 - Synthetic Minority Oversampling Technique (SMOTE)

## Aim

The aim of this experiment is to utilize the SMOTE technique to generate synthetic data in order to address the problem of class imbalance in classification tasks.

## Introduction

Imbalanced classification refers to the scenario where the distribution of classes in the dataset is highly skewed, with one class significantly outnumbering the other(s). This poses a challenge as conventional machine learning models tend to perform poorly on the minority class, often resulting in biased predictions.

## Problem Statement

Working with imbalanced datasets presents several challenges. Most machine learning algorithms tend to focus on the majority class, neglecting the minority class. As a result, the predictive performance of the model is often unsatisfactory, especially for scenarios where correct classification of the minority class is critical.

## Solution

One approach to handle imbalanced datasets is to oversample the minority class. This involves either duplicating instances from the minority class or generating synthetic instances to balance the class distribution. The Synthetic Minority Oversampling Technique (SMOTE) is a popular data augmentation technique designed specifically for addressing class imbalance. Instead of simply duplicating minority class instances, SMOTE generates synthetic samples by interpolating between existing minority class instances.

## Experiment Details

In this experiment, we will implement the SMOTE technique to generate synthetic data for the minority class. By augmenting the minority class with synthetic samples, we aim to create a more balanced dataset that can improve the performance of machine learning models, particularly on the minority class.
