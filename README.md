Gophish: Open-Source Phishing Toolkit

Gophish Logo
Build Status GoDoc

Gophish is an advanced open-source phishing framework tailored for security professionals, businesses, and penetration testers. With Gophish, conducting phishing campaigns and implementing security awareness training becomes streamlined, allowing for fast setup and efficient deployment.
Key Features

    Cross-Platform Compatibility: Available for Windows, macOS, and Linux.
    Rapid Deployment: Minimal setup required to start phishing engagements.
    Security Awareness Training: Ideal for testing organizational vulnerability to phishing threats.

Installation

Installing Gophish is straightforward. Simply download and extract the release package compatible with your operating system, then execute the binary to get started.
Building from Source

To compile Gophish from source, ensure you have Go v1.10 or higher installed. Clone the repository and build as follows:

bash

git clone https://github.com/gophish/gophish.git
cd gophish
go build

The generated gophish binary will be available in the project directory.
Docker Option

For containerized environments, Gophish is also available as an official Docker image. Get started by pulling the image from Docker Hub:

bash

docker pull gophish/gophish

More details can be found on Docker Hub.
Setup

After launching the Gophish binary, access the dashboard by navigating to https://localhost:3333 in a web browser. The log output will display the default login credentials, similar to:

plaintext

time="2020-07-29T01:24:08Z" level=info msg="Please login with the username admin and the password 4304d5255378177d"

For Gophish versions prior to v0.10.1, the default credentials are:

    Username: admin
    Password: gophish

Documentation

Comprehensive documentation is available on the official Gophish website. If you encounter any gaps in the documentation or have feature suggestions, feel free to contribute by opening an issue.
Reporting Issues

If you identify bugs, require additional features, or notice missing information in the documentation, we encourage you to submit an issue. Our team actively monitors feedback and prioritizes improvements to enhance user experience.
License

Gophish is licensed under the MIT License:

vbnet

The MIT License (MIT)
Gophish - Open-Source Phishing Framework

© 2013 - 2020 Jordan Wright

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files, to deal in the Software
without restriction, including without limitation the rights to use, copy,
modify, merge, publish, distribute, sublicense, and/or sell copies of the Software,
and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

This software is provided "AS IS", without warranty of any kind.

For more information, visit Gophish's website.
