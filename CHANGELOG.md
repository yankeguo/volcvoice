# Changelog
All notable changes to this project will be documented in this file. See [conventional commits](https://www.conventionalcommits.org/) for commit guidelines.

- - -
## v0.1.1 - 2024-11-12
#### Features
- add stream synthesize input from slice and channel - (01164dc) - GUO YANKE

- - -

## v0.1.0 - 2024-11-12
#### Bug Fixes
- correct message handling for FullServer message - (c5ca606) - GUO YANKE
- close connection on last audio chunk - (e1a3c42) - GUO YANKE
- fix arguments for voice clone - (159a5c1) - GUO YANKE
#### Documentation
- update README.md [skip ci] - (5276c5d) - GUO YANKE
- update README.md [skip ci] - (4d8e06d) - GUO YANKE
- update README.md [skip ci] - (ab0462a) - GUO YANKE
- update README.md [skip ci] - (f33a96f) - GUO YANKE
- update README.md [skip ci] - (cf205b9) - GUO YANKE
- add notes for voice clone - (fa7741c) - GUO YANKE
#### Features
- add voice_clone_synthesize - (499ba45) - GUO YANKE
- add voice_clone_upload - (ac22fad) - GUO YANKE
- add tts.Service for bi-directional stream TTS - (9907efc) - GUO YANKE
- remove cluster constants since it changes - (0297df2) - GUO YANKE
- support compression for server response - (3dc4ca2) - GUO YANKE
- complete VoiceCloneService - (b9982b6) - GUO YANKE
- complete marshalVoiceCloneRequest - (8f1fdb2) - GUO YANKE
- add client with options - (21cd78c) - GUO YANKE
#### Miscellaneous Chores
- add cog.toml - (5e0eb28) - GUO YANKE
- update logging - (38578a7) - GUO YANKE
- update .gitignore - (b0e1eaf) - GUO YANKE
- merge files in tts - (6671762) - GUO YANKE
- merge files from official demo - (93c5960) - GUO YANKE
- rename to volcvoice - (1463cc8) - GUO YANKE
- add client.go - (5d387bd) - GUO YANKE
- initialize repository - (1179b65) - GUO YANKE
#### Refactoring
- optimize code for duplex_synthesize - (4286fec) - GUO YANKE
- rename to duplex_synthesize, stream_synthesize and voice_clone_upload - (157d77e) - GUO YANKE
- flatten package - (3c3842b) - GUO YANKE
- remove single-direction stream - (8447502) - GUO YANKE
#### Tests
- rename tests - (64ec60a) - GUO YANKE
- add github actions and codecov - (4861ae8) - GUO YANKE

- - -

Changelog generated by [cocogitto](https://github.com/cocogitto/cocogitto).