# Avatar Synthesis

Two applications were developed within the SignON project.
- The first, SignON Editor, is a web-based system that allows users to generate and edit sign animations. These animations are built using a phonetic approach, which allows grammatical information to be imbued into the final message. It is also connected to previosly-crafted repositories of signs, so users can reuse signs to build more complex messages such as a combination of signs or utterances. The main repository of this work can be found [here](https://github.com/upf-gti/SignON-editor).

<p align="center"> <img src="./editor.png" height="300"> </p>

- The second, SignON Realizer, is the 3D engine that contains all the avatar movement from a phonetic representation input. This acts as the core of the previous application, and it is also used in the SignON mobile application. This application is also prepared to execute animations from glosses, by using a mapping between a gloss to the corresponding phonetic representation. By now, due to the lack of existing data, we are restricted to Dutch Sign Language (NGT). The main repository of this work can be found [here](https://github.com/upf-gti/SignON-realizer).

<p align="center"> <img src="./realizer.png" height="300"> </p>
