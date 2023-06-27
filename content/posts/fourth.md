---
title: "Building DocShield: A Decentralized Document Holder"
date: 2023-06-27T16:57:59+05:30
draft: false
---

![Docshield Logo](https://devfolio-prod.s3.ap-south-1.amazonaws.com/hackathons/d9a2e98f3dc84a7287f577f4c9f617b7/projects/929553fe72d145939baf2b280268c1f0/023bfb5a-a185-49f8-aa49-4315bd8153ad.png)

# Introduction

Welcome to another devlog post! Today, I want to share my journey of building "DocShield," a decentralized document holder. The project leverages NextJS and TailwindCSS for the user interface, MongoDB for database management, and Golang for the API. With the integration of Metamask for authentication, AES encryption for document security, IPFS for distributed file storage, and customizable access controls, DocShield aims to provide a secure and user-friendly platform for managing and sharing documents. Let's dive into the features and implementation details!

## Technology Stack

    NextJS: A React framework for building accessible and performant user interfaces.
    TailwindCSS: A utility-first CSS framework for rapid UI development.
    MongoDB: A flexible and scalable NoSQL database for efficient document storage.
    Golang: A powerful programming language used for building the API and server-side logic.
    Metamask: A browser extension that enables secure authentication through Ethereum wallets.
    AES Encryption: Advanced Encryption Standard used for encrypting documents to ensure data security.
    IPFS: InterPlanetary File System, a decentralized protocol for distributed file storage.

## Authentication with Metamask

To provide secure authentication, I integrated Metamask into DocShield. Users can connect their Ethereum wallets to authenticate and access their accounts. Metamask ensures a secure and seamless login experience while leveraging the power of blockchain technology.

## Document Encryption with AES

Data security is a top priority in DocShield. To protect sensitive documents, I implemented AES encryption. When a user uploads a document, it is encrypted using a unique encryption key. This ensures that only authorized users with the correct access controls can decrypt and view the document.

## Distributed File Storage with IPFS

Instead of relying on a centralized file storage system, DocShield utilizes IPFS for distributed file storage. When a document is uploaded, it is broken down into smaller chunks and distributed across the IPFS network. This approach ensures redundancy, fault tolerance, and improved availability of documents.

## Accessible User Interface

DocShield's user interface is built with NextJS and styled with TailwindCSS. The focus was on creating an accessible and intuitive design that caters to a wide range of users. The interface allows users to easily navigate, upload documents, manage access controls, and share files securely.

## Access Controls through Different Wallets

DocShield offers granular access controls for document sharing. Users can define different wallets or addresses that have permission to view or edit specific documents. This enables collaboration and ensures that only authorized individuals can access sensitive information.

## File Sharing through Custom Links

In addition to access controls, DocShield provides a convenient file sharing feature. Users can generate custom links for specific documents and share them securely with others. This allows external parties to access the shared document without requiring an account on the platform.

## Conclusion

Building DocShield has been an exciting journey, combining various technologies to create a decentralized document holder. With Metamask-based authentication, AES encryption, IPFS file storage, customizable access controls, and a user-friendly interface, DocShield aims to provide a secure and efficient platform for managing and sharing documents.

If you're interested in exploring the code, feel free to check out the project repository on GitHub. I hope you found this devlog post insightful and inspiring. Thank you for reading, and stay tuned for more updates on the DocShield project!