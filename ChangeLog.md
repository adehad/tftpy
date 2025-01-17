# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [0.8.2]() - 2021-08-13

<small>[Compare with 0.8.1]()</small>

### Fixed
- Fix def serverinitial to support windows ([2ed5f13](nicodemus.digitaltorque.ca:git/tftpy/commit/2ed5f1376e9d34ad47bdced2253c5089c2d1a2ef) by pucgenie).


## [0.8.1]() - 2021-06-03

<small>[Compare with 0.8.0]()</small>

### Added
- Add retires paramater to client and server sessions ([08cf590](nicodemus.digitaltorque.ca:git/tftpy/commit/08cf5909b0497ca18c218a7131f77d5761700cf1) by israelv).
- Add retires to context initializers ([f8d033c](nicodemus.digitaltorque.ca:git/tftpy/commit/f8d033c5e4fb83a856c720424c5863d8d7601c73) by israelv).

### Fixed
- Fix #109: reading binary data from sys.stdin ([f81af33](nicodemus.digitaltorque.ca:git/tftpy/commit/f81af33fcda34f1f0c12c01dcc8481f04377d1d3) by max ulidtko).


## [0.8.0]() - 2018-09-13

<small>[Compare with 0.7.0]()</small>

### Added
- Adding some boilerplate ([a646a68](nicodemus.digitaltorque.ca:git/tftpy/commit/a646a68e831dd15260dd86b44ed1005195ea0b8e) by Michael P. Soulier).
- Added a long_description ([6dd8e5d](nicodemus.digitaltorque.ca:git/tftpy/commit/6dd8e5dd4a011c9c6916600484ab6863369417f2) by Michael P. Soulier).

### Fixed
- Fixing another broken test case ([3ed50ac](nicodemus.digitaltorque.ca:git/tftpy/commit/3ed50ac7c0c50d4bab018f1a87eadb2193135113) by Michael P. Soulier).
- Fixing some broken test-cases. ([de18ed2](nicodemus.digitaltorque.ca:git/tftpy/commit/de18ed2e5c330c599498e33c4a796f645ffad5bc) by Michael P. Soulier).
- Fixing more encoding issues for python3. ([336d4e0](nicodemus.digitaltorque.ca:git/tftpy/commit/336d4e0b0e4dc38ca4b905a9d14aed56d9046a5e) by Michael P. Soulier).
- Fixing some encoding issues in python3 ([d86b9df](nicodemus.digitaltorque.ca:git/tftpy/commit/d86b9df73d3d00c0abde7acc264e89824685831e) by Michael P. Soulier).
- Fixed testclientserveruploadoptions testcase ([765c7f5](nicodemus.digitaltorque.ca:git/tftpy/commit/765c7f534c96307c71245169bb105974af38e15b) by Michael P. Soulier).
- Fix encoding position in setup.py ([e9e57a7](nicodemus.digitaltorque.ca:git/tftpy/commit/e9e57a7ebd876fc752b5c28e783d71d149c9586d) by Nick).


## [0.7.0]() - 2018-05-18

<small>[Compare with 0.6.2]()</small>

### Added
- Adding pythonioencoding environment variable to test runner. ([e05557b](nicodemus.digitaltorque.ca:git/tftpy/commit/e05557b23ad212e5526ede716cbdeeebc4f747ed) by Michael P. Soulier).
- Added logic to tftpstates.senderror to fix issue #79 ([8e0c8e3](nicodemus.digitaltorque.ca:git/tftpy/commit/8e0c8e304b8c7a813e51e792a4b51a4be5674b49) by John W Kerns).
- Added recommended imports for python3 compatibility. ([577d30f](nicodemus.digitaltorque.ca:git/tftpy/commit/577d30f36d21c64206862b3433b815f1b408c35a) by Michael P. Soulier).
- Add a context to dynamic upload_open ([b938db8](nicodemus.digitaltorque.ca:git/tftpy/commit/b938db8647f47fa4a47716a1db7a6c6e09739c7f) by Paul Weaver).
- Added tests for tsize option and fixed failures. ([a888515](nicodemus.digitaltorque.ca:git/tftpy/commit/a8885154628fb3795fcda7143db09feb437a8eef) by Michael P. Soulier).
- Adding joke of a unit test for logging. ([4b18200](nicodemus.digitaltorque.ca:git/tftpy/commit/4b182006181cc1192c419f2c46432ebdfba304f2) by Michael P. Soulier).
- Add handler to record logmsg to logfiles and stdout ([ac8cc43](nicodemus.digitaltorque.ca:git/tftpy/commit/ac8cc43d03fe232d489f23a33a741aae16c3f50e) by wlq6037).
- Adding python3 support ([77af4ea](nicodemus.digitaltorque.ca:git/tftpy/commit/77af4ea3fec68297be25cb96990040c81d2c4c4e) by Doug O'Riordan).
- Added pypi makefile target ([73c7f30](nicodemus.digitaltorque.ca:git/tftpy/commit/73c7f30b70b2c88d43222bcc4aa002db9e700814) by Michael P. Soulier).

### Changed
- Changed raise exception line to be compatible with python3 ([4bbdc8e](nicodemus.digitaltorque.ca:git/tftpy/commit/4bbdc8ea0b12f7d19b15d9a65702ba2eb4f43b92) by NWiBGRsK).
- Change an raise exception line, to be compatible with python3 ([70731ad](nicodemus.digitaltorque.ca:git/tftpy/commit/70731adcdc1e1f29352d8d74cf8b310d68bbedbd) by NWiBGRsK).

### Fixed
- Fixing closure of stdout on context close. #76 ([a430816](nicodemus.digitaltorque.ca:git/tftpy/commit/a4308162e473f2249a68afc753ce2a8e65729bcd) by Michael P. Soulier).
- Fixing zero-sized file left around by client on a file not found error. ([791def3](nicodemus.digitaltorque.ca:git/tftpy/commit/791def3f55081cebd1f27019776c628293a931fc) by Michael P. Soulier).
- Fixed bad reference to tftppacketoack in tftpy_client.py ([b85fd81](nicodemus.digitaltorque.ca:git/tftpy/commit/b85fd811e0eba85e730ea72ec5697f8a6c31d924) by Michael P. Soulier).
- Fixing 2 exceptions for python3 ([cc1880c](nicodemus.digitaltorque.ca:git/tftpy/commit/cc1880cc0503bd59edccd61ecc56cecb4c98c5ad) by Michael P. Soulier).
- Fix some deprecations and python3 incompatibilities ([b5fba7b](nicodemus.digitaltorque.ca:git/tftpy/commit/b5fba7b3059f34b20d65702e0c8d83ed0263e682) by sedrubal).
- Fixing obvious python3 errors. timeouts still not working. ([a68924f](nicodemus.digitaltorque.ca:git/tftpy/commit/a68924f2a66916b2d967b011d981259752556ae4) by Michael P. Soulier).
- Fixing some python3 syntax errors ([2537ab0](nicodemus.digitaltorque.ca:git/tftpy/commit/2537ab0dc2d416c323fcc5169698b63eee256324) by Michael P. Soulier).
- Fixing tab char ([f8a37dc](nicodemus.digitaltorque.ca:git/tftpy/commit/f8a37dc4428ac75a49c291ec15001b343bfd2d09) by Michael P. Soulier).


## [0.6.2]() - 2014-11-15

<small>[Compare with 0.6.1]()</small>

### Added
- Added a comment. ([21c0b09](nicodemus.digitaltorque.ca:git/tftpy/commit/21c0b09ab279c1c3bdd79142328110cd599da41a) by Michael P. Soulier).
- Added localip parameter for tftpclient ([fe4e86b](nicodemus.digitaltorque.ca:git/tftpy/commit/fe4e86b719f6561e5c50812a900b5ff7af741f69) by Jaroslaw Niec).
- Added a test for last change. ([75d346a](nicodemus.digitaltorque.ca:git/tftpy/commit/75d346a339768012455bff98e2b0545ab7f0ecc4) by Michael P. Soulier).
- Added tests for server api stop. ([d55b7b3](nicodemus.digitaltorque.ca:git/tftpy/commit/d55b7b3f6866df1b76f8dd88c944d633b62a37e2) by Michael P. Soulier).

### Fixed
- Fixing #11: server accept leading '/' in uploads ([3481af8](nicodemus.digitaltorque.ca:git/tftpy/commit/3481af83d7f0f298bec38e933df3991558b62184) by Nathan Bird).


## [0.6.1]() - 2013-09-27

<small>[Compare with 0.6.0]()</small>

### Added
- Adding graceful exit condition. ([d86ecb7](nicodemus.digitaltorque.ca:git/tftpy/commit/d86ecb749c17948d9d76d7aad72ba23f24e5ec5a) by Michael P. Soulier).
- Adding a tftpserver.stop() method. ([a105799](nicodemus.digitaltorque.ca:git/tftpy/commit/a10579994d3cff1ca491b8f9785ceb78dbe1343f) by Michael P. Soulier).
- Adding testcases for new file-like input and output ([b57e583](nicodemus.digitaltorque.ca:git/tftpy/commit/b57e583798be5e145f21ad0caf1c5d18f485df2a) by Michael P. Soulier).
- Adding subdirectory support. hopefully closes issue 25. ([9b655fc](nicodemus.digitaltorque.ca:git/tftpy/commit/9b655fcaa1f30dab63fc982a81c445183f101e43) by Michael P. Soulier).

### Fixed
- Fixed testcases. ([d7c0010](nicodemus.digitaltorque.ca:git/tftpy/commit/d7c001031f2391ef05d12b0659020b15bef936bd) by Michael P. Soulier).
- Fixing debug calls to be lazy when debug is off. ([6d07acb](nicodemus.digitaltorque.ca:git/tftpy/commit/6d07acb8e571fde2421a633e10bc7d1fd3bf1b45) by Michael P. Soulier).
- Fixing a testcase. ([0cab8c3](nicodemus.digitaltorque.ca:git/tftpy/commit/0cab8c3e2d9ae5730d099dc53d28aaba9e72d254) by Michael P. Soulier).
- Fixing unit tests ([86b42d1](nicodemus.digitaltorque.ca:git/tftpy/commit/86b42d14f6547b1f98615e88c0c04c5cdd975d87) by Michael P. Soulier).
- Fixing doc on website ([6359c21](nicodemus.digitaltorque.ca:git/tftpy/commit/6359c212cca4b5e2485eb796e8c6b7d24594571d) by Michael P. Soulier).
- Fixing testcase for pre python 2.7 ([51150aa](nicodemus.digitaltorque.ca:git/tftpy/commit/51150aa03aece3bfedf38f5f8d49755e9ae97e1e) by Michael P. Soulier).
- Fixing issue #26, with the server not creating the full path to the filename being uploaded. ([05e56b6](nicodemus.digitaltorque.ca:git/tftpy/commit/05e56b66a4600a5b9194f47b7f348e3278da69b6) by Michael P. Soulier).


## [0.6.0]() - 2011-07-24

<small>[Compare with 0.5.1]()</small>

### Added
- Adding retries on timeouts, still have to exhaustively test. should close issue #21 on github. ([1e74abf](nicodemus.digitaltorque.ca:git/tftpy/commit/1e74abf010088abd4bab27de74778e41393911dd) by Michael P. Soulier).
- Adding a server download state test to the unit tests. ([f6442eb](nicodemus.digitaltorque.ca:git/tftpy/commit/f6442eb4e40fe19ab7d210d068c8a63b025d12c9) by Michael P. Soulier).

### Fixed
- Fixing issue #3, expanding unit tests. ([04aaa2e](nicodemus.digitaltorque.ca:git/tftpy/commit/04aaa2ef9ff6a09d39d67a1ee42b359e244afd24) by Michael P. Soulier).
- Fixing some pyflakes complaints ([40977c6](nicodemus.digitaltorque.ca:git/tftpy/commit/40977c6f74496be16087767b8444af2b34f933d5) by Michael P. Soulier).
- Fixes issue #23, breaking up tftpstates into tftpstates and tftpcontexts. ([add4440](nicodemus.digitaltorque.ca:git/tftpy/commit/add444006ca53d1469ef4f333e9bbbaea05a8ac1) by Michael P. Soulier).
- Fixing issue #9, removing blksize option from client if not supplied. ([949c998](nicodemus.digitaltorque.ca:git/tftpy/commit/949c998648a9e3e1b00a7cb218d8f8093a48ac48) by Michael P. Soulier).
- Fixing issue #16 on github, server failing to use timeout time in checktimeout() method. ([a43773e](nicodemus.digitaltorque.ca:git/tftpy/commit/a43773e26cb056bc1db6392f2ffa9dedcabd4548) by Michael P. Soulier).
- Fixing a file descriptor leak. closes issue 22. ([6fd9391](nicodemus.digitaltorque.ca:git/tftpy/commit/6fd9391ad86fe58cf73dabce452d5d14c0d9ac32) by Michael P. Soulier).
- Fix exceptions propagating out of tftpserver.listen() ([a6cff4f](nicodemus.digitaltorque.ca:git/tftpy/commit/a6cff4f0b23068218849e44718e7255b634a9872) by Kenny Millington).
- Fixing setnextblock to roll over at `2**16 - 1` instead of `2**16`, which was causing problems when uploading large files. ([45185ed](nicodemus.digitaltorque.ca:git/tftpy/commit/45185ed44c53fefc9450a4e307eb66373f30b7a6) by Michael P. Soulier).


## [0.5.1]() - 2010-07-14

<small>[Compare with 0.5.0]()</small>

### Added
- Added simple doc examples and install info. ([e35cd2d](nicodemus.digitaltorque.ca:git/tftpy/commit/e35cd2d60c857d3d85350993606149f5622aab18) by Michael P. Soulier).
- Adding initial sphinx docs ([402b2ae](nicodemus.digitaltorque.ca:git/tftpy/commit/402b2ae4c45f83dfafc6d4ed267043be537f6aa8) by Michael P. Soulier).
- Adding support for input/output as stdin/stdout ([58623df](nicodemus.digitaltorque.ca:git/tftpy/commit/58623df7d08fa88c9b869f89798e85b6c5e626e8) by Michael P. Soulier).

### Fixed
- Fixing typo in unit test ([0b54068](nicodemus.digitaltorque.ca:git/tftpy/commit/0b5406865aab547f9b4c3839c558a68012bec78c) by Michael P. Soulier).
- Fixing failure to set default blocksize if options were provided but blksize was not one of them. ([f4a3ff6](nicodemus.digitaltorque.ca:git/tftpy/commit/f4a3ff6356a32485b7c1cf98b188e0886390387e) by Michael P. Soulier).
- Fix incorrectly assigned state transition ([1a2b556](nicodemus.digitaltorque.ca:git/tftpy/commit/1a2b55677135e64c2a623b46b6861f2e5c726f2f) by Patrick Oppenlander).
- Fix divide by zero in speed calculation for short transfers ([360b0b9](nicodemus.digitaltorque.ca:git/tftpy/commit/360b0b928d6f8b913fdcdbfa30a8210d996c6c71) by Patrick Oppenlander).
- Fixing the license in the setup.py ([d4c15e1](nicodemus.digitaltorque.ca:git/tftpy/commit/d4c15e10eaf8fb6fc6fe3acef770b275e287134e) by Michael P. Soulier).


## [0.5.0]() - 2010-05-10

<small>[Compare with 0.4.6]()</small>

### Added
- Adding patch for dynamic content from alex ? <yix@ya.ru> ([5ee5f63](nicodemus.digitaltorque.ca:git/tftpy/commit/5ee5f63f9b2b978972aa2f3035ec458a656b036b) by Michael P. Soulier).
- Adding website ([abf0f1f](nicodemus.digitaltorque.ca:git/tftpy/commit/abf0f1fa153c12104bebd9d1a1ddf700132ed52b) by Michael P. Soulier).

### Changed
- Changed licenses to the mit license ([a80639c](nicodemus.digitaltorque.ca:git/tftpy/commit/a80639c7e2b23476162bcee716be73062543ddf1) by Michael P. Soulier).

### Fixed
- Fixing buffering issue in upload. uploads work now. ([faebd44](nicodemus.digitaltorque.ca:git/tftpy/commit/faebd4497843d8cb31ee50c33842d79ff8093654) by Michael P. Soulier).
- Fixed an obvious error introduced with the dyn_file_func merge ([4a4f53a](nicodemus.digitaltorque.ca:git/tftpy/commit/4a4f53a107e09f3c6368d56192337de6339b8c54) by Michael P. Soulier).
- Fix dyn_file_func (was broken?) fix error message (filename was not displayed) ([72c4769](nicodemus.digitaltorque.ca:git/tftpy/commit/72c47698eb7a8fda3d3082e2c5e5438e2a437eda) by Alexey Loshkarev).
- Fixing some log messages and bad variable references. ([ce7fc32](nicodemus.digitaltorque.ca:git/tftpy/commit/ce7fc323c6dd7d29f3e8ad4bb73e41e3c07ded58) by Michael P. Soulier).
- Fixed server metrics summary. ([3ae3b31](nicodemus.digitaltorque.ca:git/tftpy/commit/3ae3b31bf40bcf39e129b4b079f1b131d5bed921) by Michael P. Soulier).
- Fixing up some of the upload code. ([03e4e74](nicodemus.digitaltorque.ca:git/tftpy/commit/03e4e748293070ac37fb7fe88abc8b915d84be96) by Michael P. Soulier).
- Fixing a merge error in rebase ([c61ca17](nicodemus.digitaltorque.ca:git/tftpy/commit/c61ca171db8945105c3b2fb25f3e510ba18e6a7d) by Michael P. Soulier).
- Fixed bug in tidport handling, and lack of oack response. ([410e14c](nicodemus.digitaltorque.ca:git/tftpy/commit/410e14c430cb55bc705098046c13e36bd21febad) by Michael P. Soulier).
- Fixing oack handling with new state machine. ([874fef5](nicodemus.digitaltorque.ca:git/tftpy/commit/874fef5aae95c349e79e0405869dada70098624b) by Michael P. Soulier).
- Fixed tftpclient with new state machine. ([5072f6d](nicodemus.digitaltorque.ca:git/tftpy/commit/5072f6d93c6fe5ba4f215e2fe6d646594714ef50) by Michael P. Soulier).
- Fixing bogus warnings in options handling. ([bc55a17](nicodemus.digitaltorque.ca:git/tftpy/commit/bc55a17f34124db066978fe4f13918660050e790) by Michael P. Soulier).
- Fixing tftproot configured for server as a relative path. ([d058642](nicodemus.digitaltorque.ca:git/tftpy/commit/d05864202541cc5fda0e71292627cbd23861c4f3) by Michael P. Soulier).
- Fixed the use of the tsize option in rrq packets. ([ca7a06a](nicodemus.digitaltorque.ca:git/tftpy/commit/ca7a06a09bbfee3f623d157df9c588b52fecf4ab) by Michael P. Soulier).


## [0.4.6]() - 2008-10-06

<small>[Compare with first commit]()</small>

### Added
- Adding transfer size option patch from kuba kończyk. patch 2018609 in sf tracker. ([8a0162b](nicodemus.digitaltorque.ca:git/tftpy/commit/8a0162b31739bc05bcec1b846834de33f5830b37) by Michael P. Soulier).
- Adding upload patch from lorenz schori - patch 1897344 in sf tracker ([6730280](nicodemus.digitaltorque.ca:git/tftpy/commit/67302801eba3b0d939c0b5d04b5b6d654ed68101) by Michael P. Soulier).
- Adding epydoc target. ([d8730c7](nicodemus.digitaltorque.ca:git/tftpy/commit/d8730c7df4e179430200a1655d4dffcf7c9ccff4) by msoulier).
- Added a check for rogue packets in the server. ([07906cd](nicodemus.digitaltorque.ca:git/tftpy/commit/07906cdbd96865cb9d3688cc1e463d7730d62c20) by msoulier).
- Added server to package. ([15023eb](nicodemus.digitaltorque.ca:git/tftpy/commit/15023eba5754f771da2af1679fa5b6020351c320) by msoulier).
- Added lots in the server to support a download, with timeouts. not yet tested with a client, but the damn thing runs. ([5cfbae3](nicodemus.digitaltorque.ca:git/tftpy/commit/5cfbae3dc795ce0029bc8d8b2e368202e3fbc3a1) by msoulier).
- Added some security checks around the tftproot. further fleshed-out the handler. still not actually starting the transfer. ([6f186f2](nicodemus.digitaltorque.ca:git/tftpy/commit/6f186f2a3304154cb35f901220927d3c22922a13) by msoulier).
- Added --debug option to sample client. ([aece5aa](nicodemus.digitaltorque.ca:git/tftpy/commit/aece5aaf2ec46479f1c1a81e2763083fd3d0eb83) by msoulier).
- Adding license ([204cce4](nicodemus.digitaltorque.ca:git/tftpy/commit/204cce4fbb74a014d9a065c885d62e8a1d9ed3a6) by msoulier).
- Adding changelog ([4fc510b](nicodemus.digitaltorque.ca:git/tftpy/commit/4fc510bcbf895842f4f9354ca71878e62708e35d) by msoulier).
- Added testcase for tftppacketfactory. ([8e6cd77](nicodemus.digitaltorque.ca:git/tftpy/commit/8e6cd77aa7d1168459e12f098c70bbb53365bff4) by msoulier).
- Added some info statements regarding option negotiation. ([0528b1b](nicodemus.digitaltorque.ca:git/tftpy/commit/0528b1bdbc5af2359b35d841052acef64c1cce5b) by msoulier).
- Adding makefile ([08af50a](nicodemus.digitaltorque.ca:git/tftpy/commit/08af50ac0e78308c388bf5790d44652cb79a8295) by msoulier).
- Added test for wrq packet ([2e42f99](nicodemus.digitaltorque.ca:git/tftpy/commit/2e42f990c0fb53769d8a3f680648f98eb873ce6a) by msoulier).
- Added confirmation of incoming traffic to known remote host. ([c24bba2](nicodemus.digitaltorque.ca:git/tftpy/commit/c24bba272f4f0d0b9e6814d24ec0446cec1cf6f4) by msoulier).
- Added seconds to logs ([09de253](nicodemus.digitaltorque.ca:git/tftpy/commit/09de253d8fbf6d2a74ea1cf8b78112a8c2e85698) by msoulier).
- Added oack packet, and factored-out client code. ([88c387b](nicodemus.digitaltorque.ca:git/tftpy/commit/88c387b1ec8a45f35daf8366740966ca9d7bc4ed) by msoulier).

### Changed
- Changed the port variables to something more intelligent. ([104dfe0](nicodemus.digitaltorque.ca:git/tftpy/commit/104dfe03cdfd1d53879a165512c46562fef52676) by msoulier).

### Fixed
- Fix for bug 1967647, referencing self.sock instead of sock. ([caff30d](nicodemus.digitaltorque.ca:git/tftpy/commit/caff30dda64b00674f9d574d085ce1992e5ac8d1) by msoulier).
- Fix for [ 1932310 ] security check always fail for windows. ([70f22b1](nicodemus.digitaltorque.ca:git/tftpy/commit/70f22b1ca1f8aa8cbb75bfb0cc3e3eafdf77368f) by msoulier).
- Fixed division by zero error in rate calculations in download function of client. thanks to stefaan vanheesbeke for the report. ([596af40](nicodemus.digitaltorque.ca:git/tftpy/commit/596af4075fe1fb4c051e9f60ef7ef7308f05f4c3) by msoulier).
- Fix for bug [ 1932330 ] binary downloads fail in windows. ([3b1bae3](nicodemus.digitaltorque.ca:git/tftpy/commit/3b1bae3470180251ee3118ff35756a80cbbdf64b) by msoulier).
- Fixing 1851544 - server not tolerant of unsupported options thanks to landon jurgens for the report. ([f8af287](nicodemus.digitaltorque.ca:git/tftpy/commit/f8af287f32fdaf5fbd00cc835fb810987c95e5b6) by msoulier).
- Fixing string/integer comparison. thanks to simon p. ditner, bug #1755146. ([955ced3](nicodemus.digitaltorque.ca:git/tftpy/commit/955ced37478516995973c47388f5eb0347c3aa25) by msoulier).
- Fixed unit test for factory ([bb47795](nicodemus.digitaltorque.ca:git/tftpy/commit/bb47795b70ada8ba6880946f5547f7a858536781) by msoulier).
- Fixing install location of library. ([6eb1501](nicodemus.digitaltorque.ca:git/tftpy/commit/6eb1501242dd3c01f9fc62e9c36e594a6e497005) by msoulier).
- Fixed a bug in handling block number rollovers. ([d5b7276](nicodemus.digitaltorque.ca:git/tftpy/commit/d5b7276fb940ce82f275aa8234164a4d8ce855cd) by msoulier).
- Fixing poor tid implementation. ([15c5a0f](nicodemus.digitaltorque.ca:git/tftpy/commit/15c5a0f7c6130ab05ebac6072f94f39560afa963) by msoulier).
- Fixed broken decode, and adjusted the client options. ([6ebd6fc](nicodemus.digitaltorque.ca:git/tftpy/commit/6ebd6fcbc88ad78072bfdcb811faf48493483760) by msoulier).
- Fixed handling of port ([e771f67](nicodemus.digitaltorque.ca:git/tftpy/commit/e771f670fb35d07c0d5267e9ecccdb394212f9ee) by msoulier).
- Fixed poor eof detection ([0a13eb5](nicodemus.digitaltorque.ca:git/tftpy/commit/0a13eb5716d2c6307361be42d7ec4ca1f57b18c4) by msoulier).

### Removed
- Removed redundant comparison. ([2a98d72](nicodemus.digitaltorque.ca:git/tftpy/commit/2a98d725401609ac9ab7ece6428a875e71e05d50) by msoulier).
- Removed mention of sorceror's apprentice problem. ([5c52975](nicodemus.digitaltorque.ca:git/tftpy/commit/5c52975f5fa07bd4d540d3b73042b40077ec3ca3) by msoulier).
