<!--
Copyright 2019 The Google Earth Engine Community Authors

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
-->

# Agentic Analysis in Google Earth Engine

I have forked the earthengine-community repository to demonstrate the use of coding agents in Google Earth Engine, developed by Simon Ilyuschenko. The demo shows how you can interact with the GEE data catalog and ask the agent to perform any number of spatial or image analysis tasks. This demo uses the python API, not the javascript GUI. The backend intelligence is powered by Gemini, but you could use other LLM APIs such as OpenAI or Anthropic. 


The directory for EE agent stuff is [/experimental/functionsmith](https://github.com/jeffgillan/earthengine-community/tree/master/experimental/functionsmith). To have a play with agentic EE, check out this demo jupyter notebook
[![Open Colab Notebook](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jeffgillan/earthengine-community/blob/master/experimental/functionsmith/ee_companion.ipynb). 

For the demo to work, the user needs to have **1.** an [Earth Engine Project ID](https://code.earthengine.google.com/register), and **2.** a [Gemini API Key](https://ai.google.dev/gemini-api/docs/api-key). Both of these items are free to obtain. 

These two items needs to be saved as [Colab Secrets](https://colab.sandbox.google.com/github/google-gemini/cookbook/blob/main/quickstarts/Authentication.ipynb)

<img src="https://github.com/jeffgillan/earthengine-community/blob/master/experimental/functionsmith/colab_secrets.png" width=400>

<br/>
<br/>
<br/>
<br/>
<br/>

## Google Earth Engine Community <!--[![Build Status](https://travis-ci.org/google/earthengine-community.svg?branch=master)](https://travis-ci.org/google/earthengine-community)-->

This repository contains content submitted and/or maintained by the Earth Engine
developer community.

## Community Tutorials

* [Browse tutorials][tutorials]
* [Request a tutorial][request]
* [Submit a tutorial][write]

Files added to [`tutorials/`][folder] will appear under the
[community tutorials section][tutorials] of the Earth Engine Developer's Guide.

## Contributing

We encourage you to join the team of [Earth Engine Community contributors][contributors]!

Visit the [contributing page][contribute] to learn how. ✏️

[folder]: https://github.com/google/earthengine-community/tree/master/tutorials
[tutorials]: https://developers.google.com/earth-engine/tutorials/community/explore
[contribute]: https://github.com/google/earthengine-community/blob/master/CONTRIBUTING.md
[request]: https://github.com/google/earthengine-community/issues/new?title=Tutorial%20Request:%20<title>&body=Description%0A%0ATechnical%20Level%0Abeginner%20%7C%20intermediate%20%7C%20advanced%0A%0ALength%0Ashort%20(<%20250%20words)%20%7C%20medium%20(250-500%20words)%20%7C%20long%20(1000%20words+)%0A
[write]: https://developers.google.com/earth-engine/tutorials/community/write
[cca]: https://creativecommons.org/licenses/by/4.0/
[apache]: http://www.apache.org/licenses/LICENSE-2.0
[authors]: https://github.com/google/earthengine-community/blob/master/AUTHORS
[contributors]: https://github.com/google/earthengine-community/graphs/contributors
