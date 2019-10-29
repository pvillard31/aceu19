# ApacheCon Europe 2019 - Running visual quality inspection at the edge with Apache NiFi & MiNiFi

This is the repository covering the talk I gave in Berlin on the 23rd of October 2019 about running visual quality inspection at the edge with Apache NiFi & MiNiFi.

## The story
- Article on [Medium](https://medium.com/@pierre.villard/running-visual-quality-inspection-at-the-edge-with-google-cloud-and-apache-nifi-minifi-45282ce7af2d) (or on my [website](https://pierrevillard.com/2019/10/29/running-visual-quality-inspection-at-the-edge-with-google-cloud-and-apache-nifi-minifi/))

## Introduction

Apache NiFi is an easy to use, powerful, and reliable system to process and distribute data. Apache NiFi supports powerful and scalable directed graphs of data routing, transformation, and system mediation logic. MiNiFi — a subproject of Apache NiFi — is a complementary data collection approach that supplements the core tenets of NiFi in data flow management, focusing on the collection of data at the source of its creation.

In this talk I present how Apache NiFi & MiNiFi can be used in combination with Google Cloud AutoML Vision to implement a visual quality inspection system. The idea is to demonstrate the possibilities to interact with edge devices while leveraging cloud services in a real world use case.

Follow me on Twitter for more about Apache NiFi - [@pvillard31](https://twitter.com/pvillard31)

## Some links worth reading

- [Apache NiFi](https://nifi.apache.org/) - [Github](https://github.com/apache/nifi)
- [Apache MiNiFi](https://nifi.apache.org/minifi/index.html) - [Github MiNiFi Java](https://github.com/apache/nifi-minifi) - [Github MiNiFi C++](https://github.com/apache/nifi-minifi-cpp)
- [Google Cloud Vision](https://cloud.google.com/vision/)
- [Google Coral](https://coral.withgoogle.com)
- and if you really have time... [my blog](https://www.pierrevillard.com/)

## Video, audio, slides...

- [Slides of my presentation](./slides/ACEU19-NiFi-MiNiFi-Visual_Quality_Inspection_At_The_Edge.pdf)
- Video & audio (soon)

## Versions

- Apache NiFi 1.9.2
- Apache MiNiFi 0.5.0

## What is this about?

Picture this: you are in a factory making cookies... you have hundreds of cookies going through your production lines per second and you want to make your customers happy! Problem: a broken cookie makes an unhappy customer! So you want a way to detect the broken cookies before they get into the final packaging.

Here I take the example of cookies, but it could really be anything related to visual quality inspection in the retail, manufacturing, etc industries.

# THE CONTENT IS COMING! I PROMISE ;)
