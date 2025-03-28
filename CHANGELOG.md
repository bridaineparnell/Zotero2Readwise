# CHANGELOG


## v0.1.0 (2025-03-28)

### Bug Fixes

- :ambulance: use library path import instead of local one
  ([`b00d2da`](https://github.com/bridaineparnell/Zotero2Readwise/commit/b00d2da8fefc1e5bb14aed0d11fa99bcc58cb896))

- :memo: update an oversight in the help
  ([`ef9ad94`](https://github.com/bridaineparnell/Zotero2Readwise/commit/ef9ad946941a0c1be5d769a263e35cb3f7c3aba6))

- Add `len`
  ([`59d3fad`](https://github.com/bridaineparnell/Zotero2Readwise/commit/59d3fadfe6a730deb86f76df486fcf54d3138aab))

- Adding spaces
  ([`e73352d`](https://github.com/bridaineparnell/Zotero2Readwise/commit/e73352d7ca7de9aa60c22958e2ce55ff35ba26e7))

- An oversight in `Zotero2Readwise` class method `run()` (previously `run_all())`
  ([`e2b1336`](https://github.com/bridaineparnell/Zotero2Readwise/commit/e2b133634372b44cefc728923ae7ef384c69adda))

- Check of max_length first
  ([`5d69300`](https://github.com/bridaineparnell/Zotero2Readwise/commit/5d693001a84413510c451a6e0f6841197f0dd64b))

Only truncate if needed. Make code more readable.

- Creator/author field
  ([`3053550`](https://github.com/bridaineparnell/Zotero2Readwise/commit/305355066773e2009f2c865cc53fee56d2dd9211))

If there are more than three authors, replace the rest with "et al."

- Empty
  ([`5ad6394`](https://github.com/bridaineparnell/Zotero2Readwise/commit/5ad6394b6cec88e3fd9801206abd87ad6f7dfab4))

- Empty commit
  ([`53db8e0`](https://github.com/bridaineparnell/Zotero2Readwise/commit/53db8e0fa14e06df4c8f4f9bf276d9d32d0c34cf))

- Empty commit for new release
  ([`7fa1b2b`](https://github.com/bridaineparnell/Zotero2Readwise/commit/7fa1b2beca4d41b5dfdabc753766cf82a9eaccba))

- Empty commit for new release
  ([`c1038c3`](https://github.com/bridaineparnell/Zotero2Readwise/commit/c1038c34a4880373b60254161df734443ed9c049))

- Empty commit for new release
  ([`65e2f44`](https://github.com/bridaineparnell/Zotero2Readwise/commit/65e2f444dfab59dd6704404d18e9742d0d591a4d))

- Empty commit to build a new release for PR#77
  ([`7375368`](https://github.com/bridaineparnell/Zotero2Readwise/commit/7375368afd4657eda37b6662bc1f12bc07018aab))

- Enusuring backward compatibility
  ([`0d5197c`](https://github.com/bridaineparnell/Zotero2Readwise/commit/0d5197ce1f648945bdfebf109d98f4c350f8166b))

To prevent the occurrence of duplicate entries in Readwise, we will amend the authors' names to 'et
  al.' exclusively in instances where their works have not been previously imported.

- Get non-empty objects from ZoteroItem (so that we have a JSON serializable object)
  ([`6b79fc9`](https://github.com/bridaineparnell/Zotero2Readwise/commit/6b79fc9bf457acd78287a8f0cbe1800f335e52fc))

- Ignore highlights more than 8191 characters (readwise limit for a highlight.)
  ([`7503324`](https://github.com/bridaineparnell/Zotero2Readwise/commit/7503324150d50db72abd3c3cbfda8b469a7d596d))

- Latest correct version. add debugging printouts
  ([`9089fe1`](https://github.com/bridaineparnell/Zotero2Readwise/commit/9089fe1adfe738ceffa6e9f6750feb62695c57be))

- Manual tagging
  ([`c2ae640`](https://github.com/bridaineparnell/Zotero2Readwise/commit/c2ae6404ecc5384b206e5b1e0b14d350a2e7661a))

- Merge pull request #28 from stefanku/master
  ([`ea16ffa`](https://github.com/bridaineparnell/Zotero2Readwise/commit/ea16ffaf1c911b693095e68773771a7ac408fc4f))

Update zotero.py

- Merge pull request #71 from jmhammond/master
  ([`45a79f7`](https://github.com/bridaineparnell/Zotero2Readwise/commit/45a79f74c1eb1490cf15af29d98ff9a1f0b7bfd1))

Fixes key error in metadata and ignores ink

- Minor changes to release a new pkg after merging
  ([`7b94b33`](https://github.com/bridaineparnell/Zotero2Readwise/commit/7b94b33e97d7ee6481fb357006c818504f6da2e4))

- Project details
  ([`502806c`](https://github.com/bridaineparnell/Zotero2Readwise/commit/502806cceb8f03a8bc2ae2d3f6d79a202d7e9452))

- Python semantic release repo name
  ([`236d47c`](https://github.com/bridaineparnell/Zotero2Readwise/commit/236d47c096e2bc6d2c5c83208277ee72d02acc8c))

- Remove category from Readwise source_url
  ([`0ed6118`](https://github.com/bridaineparnell/Zotero2Readwise/commit/0ed61182b935af8fd28e7fd0867b048163a69550))

- Remove filtering zotero items upto 5 items.
  ([`4f3e5e0`](https://github.com/bridaineparnell/Zotero2Readwise/commit/4f3e5e097ec9f6b99e709c1b3be306802a672023))

- Semantic release configs in pyproject.toml
  ([`50a844d`](https://github.com/bridaineparnell/Zotero2Readwise/commit/50a844d282dbb3fb773977cc0810354794c10c9a))

- Test a patch release
  ([`8ebb3c8`](https://github.com/bridaineparnell/Zotero2Readwise/commit/8ebb3c8f279e5d74ca57e691e154c702abd8af5f))

- Update iPython to resolve a security bug.
  ([`12b1908`](https://github.com/bridaineparnell/Zotero2Readwise/commit/12b19084154e4ecaebd5d5e3d05d6fd0c68b0996))

- Use alternate link Zotero (`https://www.zotero.org/username/items/<itemKey>`) that has a html
  content instead of self link (`https://api.zotero.org/users/<userID>/items/<itemKey>`) that
  contains a JSON content and calls the API.
  ([`3310ad1`](https://github.com/bridaineparnell/Zotero2Readwise/commit/3310ad130afdcc977a8eb771712950d0d70064d1))

- Use more distinct step id for GHA step
  ([`5d30a25`](https://github.com/bridaineparnell/Zotero2Readwise/commit/5d30a2536c5046e4f175507fd5d68a86d1f2c264))

- Versions and update GH Token secret
  ([`073a57d`](https://github.com/bridaineparnell/Zotero2Readwise/commit/073a57d4f62c6a36bb4907cedee6c52c237b84eb))

- **gha**: Try another fix for workflow
  ([`cb2f88f`](https://github.com/bridaineparnell/Zotero2Readwise/commit/cb2f88f8c295bcdfb926089e798c1f71467c288b))

- **gha**: Update the workflow for package release
  ([`b6cbda7`](https://github.com/bridaineparnell/Zotero2Readwise/commit/b6cbda71e79d4a75fcd507611e9507c01327962b))

- **pyproject**: Version bump config
  ([`566989b`](https://github.com/bridaineparnell/Zotero2Readwise/commit/566989be781ba7a7062e500ada646918c6d2e60a))

### Build System

- :construction_worker: add `zotero2readwise` as a package to `pyproject.toml`.
  ([`d45c77d`](https://github.com/bridaineparnell/Zotero2Readwise/commit/d45c77da04f4fd367021e88abb1bc7bb2dc81c95))

Update pre-commit

- **GitHub Actions**: :building_construction: pinpoint semantic releaset GH Action
  ([`fb5f6cf`](https://github.com/bridaineparnell/Zotero2Readwise/commit/fb5f6cf644c19d51a9c90f1df54820ae7abc1c92))

### Chores

- :see_no_evil: update `.gitignore`
  ([`9efe4f5`](https://github.com/bridaineparnell/Zotero2Readwise/commit/9efe4f5375675f2be52bde3831e1c6f0b0be0d82))

- Ignore json files
  ([`42319cb`](https://github.com/bridaineparnell/Zotero2Readwise/commit/42319cb1c69a89861784871e8488709df594dbe9))

### Documentation

- Add instructions to README.
  ([`925ecf9`](https://github.com/bridaineparnell/Zotero2Readwise/commit/925ecf9d3283d8c07faa5b05c5e04ae89164622a))

- Define Zotero2ReadwiseError exception object.
  ([`7d5022a`](https://github.com/bridaineparnell/Zotero2Readwise/commit/7d5022a0ebc28e170e07dc004042981b2be7e314))

- Improve printouts for both Zotero and Readwise operations
  ([`5a22717`](https://github.com/bridaineparnell/Zotero2Readwise/commit/5a22717987a509c123b233dfd33aeded1a9902cd))

### Features

- Add `ZoteroAnnotationsNotes` to `Readwise` object.
  ([`8f34989`](https://github.com/bridaineparnell/Zotero2Readwise/commit/8f349894c2a65dc3a0df5e60a1fd2ec32047f72f))

- Define ReadwiseAPI and ReadwiseHighlight dataclasses.
  ([`8d5488f`](https://github.com/bridaineparnell/Zotero2Readwise/commit/8d5488f0c8cfbe5f4897c59c7e251ac10203c7c7))

- Define Zotero2Readwise class that runs everything.
  ([`8361426`](https://github.com/bridaineparnell/Zotero2Readwise/commit/8361426d8c321162333fb44432f76cefb310e231))

- Define ZoteroAnnotationsNotes. Add `sanitize_tag()` helper function.
  ([`d5f27d6`](https://github.com/bridaineparnell/Zotero2Readwise/commit/d5f27d602a9b44d38b0c13974bb4acd73f2bc915))

Comment out ZoteroAnnotation dataclass.

- Define ZoteroItem dataclass and use that to format the zotero annotations (separate formatting
  from Readwise class).
  ([`cfa1b12`](https://github.com/bridaineparnell/Zotero2Readwise/commit/cfa1b1277d7dcae15c687a96aac86115b1e7e4d8))

- Empty commit to trigger release build
  ([`7c7577c`](https://github.com/bridaineparnell/Zotero2Readwise/commit/7c7577c0e16dbc86e47f8906d0b8ca80168b185f))

- Functions to retrieve all annotations and notes from Zotero.
  ([`cafb998`](https://github.com/bridaineparnell/Zotero2Readwise/commit/cafb9982827c5f85ddb0a6c65ec21f2e21747b00))

- Major changes to Readwise class.
  ([`ea27b8c`](https://github.com/bridaineparnell/Zotero2Readwise/commit/ea27b8c0004f6618803452a2df33d7af26a054eb))

- Merge pull request #47 from noeleont/feat/filter-color
  ([`c6af8b2`](https://github.com/bridaineparnell/Zotero2Readwise/commit/c6af8b2d16cffe46e29e985bc77f24a4b3401799))

Add color filter support

- Refactor `Zotero2Readwise.run()` to pass a custom number of Zotero annotations and notes instead
  of running all.
  ([`7c8a337`](https://github.com/bridaineparnell/Zotero2Readwise/commit/7c8a3372b642e3056c5279dcfa06470eb6981f34))

- Save failed items to a json file. Add printouts.
  ([`e107fc0`](https://github.com/bridaineparnell/Zotero2Readwise/commit/e107fc0434b75d021c12674556d83e0df9947649))

- **since**: Finish functionallity
  ([`349eaa6`](https://github.com/bridaineparnell/Zotero2Readwise/commit/349eaa6a6570e85ee6aea6121a8988f0c9d392e0))

- get_all_zotero_items use since - refactor: retrieve_all_* to one function with item_type as
  parameter

- **since**: Only sync since last sync
  ([`42b3449`](https://github.com/bridaineparnell/Zotero2Readwise/commit/42b3449d93f69f759c54a5bcb3ac82e18b463f19))

Storing the last synchronization timestamp in a file allows for incremental syncing, efficiently
  updating only the new highlights since the last sync, ideal for large collections.

### Refactoring

- Change if condition in the GHA.
  ([`ff27c6f`](https://github.com/bridaineparnell/Zotero2Readwise/commit/ff27c6fb0760025a97434e7f16d808ef32f8798e))

- Remove unrelated branches
  ([`767c598`](https://github.com/bridaineparnell/Zotero2Readwise/commit/767c598c4e1dc6ba72aa604cb59ca3085a86aaea))

- Update failed directory path. Indent the output json files for cleaner output.
  ([`8cfee3d`](https://github.com/bridaineparnell/Zotero2Readwise/commit/8cfee3dd28e3fb008236aa56ce66dff34c77bc75))

- **GitHub Actions**: :building_construction: release after merging to master
  ([`412988f`](https://github.com/bridaineparnell/Zotero2Readwise/commit/412988f4b07f424f7e25802818f852e413b10b34))
