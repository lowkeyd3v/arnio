# Changelog

## [1.10.0](https://github.com/lowkeyd3v/arnio/compare/v1.14.0...v1.10.0) (2026-05-18)


### Features

* add ArFrame __contains__ support ([2e63c39](https://github.com/lowkeyd3v/arnio/commit/2e63c396730caef6e6b2d8d238c046ea22d889bc))
* add ArFrame preview method ([814102e](https://github.com/lowkeyd3v/arnio/commit/814102e35b153cf75b3a759a5e33867edfe03321))
* add ArFrame select_columns helper ([fff406d](https://github.com/lowkeyd3v/arnio/commit/fff406d9a10943cb6f2bd76d32240933da90ed51))
* add ArFrame.select_dtypes() for type-based column selection ([1c56e23](https://github.com/lowkeyd3v/arnio/commit/1c56e2369b3abf3fc80e2448f912fd3194b9c63b))
* add benchmark regression reporting ([#554](https://github.com/lowkeyd3v/arnio/issues/554)) ([83b9ee5](https://github.com/lowkeyd3v/arnio/commit/83b9ee5c8cf75477ebb476f1fb3f13654eceab3a))
* add bounded profiling sample_size validation ([1e31269](https://github.com/lowkeyd3v/arnio/commit/1e3126986bdc21e128fc734a71a77aa7f242441a))
* add clip_numeric cleaning helper ([4022449](https://github.com/lowkeyd3v/arnio/commit/4022449c7bbe5e31c94e756ff29a36b4c274a232))
* add column existence validation helper ([517d1e0](https://github.com/lowkeyd3v/arnio/commit/517d1e07d3b19252027ecdfac23d17b19e0aa793))
* add composite uniqueness validation support ([#495](https://github.com/lowkeyd3v/arnio/issues/495)) ([8b11e19](https://github.com/lowkeyd3v/arnio/commit/8b11e19180b97fde1c380857e702d78dc7df8fc8))
* add conditional required validation ([34c75a2](https://github.com/lowkeyd3v/arnio/commit/34c75a20efb0e06acc2d036296e25eb484b090df))
* add confidence metadata to cleaning suggestions ([2a78f8a](https://github.com/lowkeyd3v/arnio/commit/2a78f8a09d36147ce58f554a153340a60cb888fd))
* add CountryCode schema validator ([#487](https://github.com/lowkeyd3v/arnio/issues/487)) ([14a77e5](https://github.com/lowkeyd3v/arnio/commit/14a77e532409bffc0fdef85fbbbaaa798782dde7))
* add data quality engine ([6053ab9](https://github.com/lowkeyd3v/arnio/commit/6053ab93fa29b706a20f5fd8d905f046fedb36c5))
* add data quality engine ([f8abb2f](https://github.com/lowkeyd3v/arnio/commit/f8abb2f8202e9d1fa394a2e1e97576f003d113b0))
* add DataQualityReport markdown export ([20b2f68](https://github.com/lowkeyd3v/arnio/commit/20b2f68c0fb29516366ca753327896a8eaba6392))
* add Date schema field ([c52ac18](https://github.com/lowkeyd3v/arnio/commit/c52ac18fff979ef5b49b04a00b8d6d8faa4b933d))
* add DateTime schema field ([05c26be](https://github.com/lowkeyd3v/arnio/commit/05c26bebf1cf79bbdbb98157dba1618c61abd08e))
* add Decimal conversion policy ([97b1a1c](https://github.com/lowkeyd3v/arnio/commit/97b1a1cc0ede5fbf0aef4176339fa4b2cf4cfed0))
* add drop constant columns ([#357](https://github.com/lowkeyd3v/arnio/issues/357)) ([3e13d3d](https://github.com/lowkeyd3v/arnio/commit/3e13d3d576add9fd8113cdf185ca08e61e75c4ee))
* add filter_rows pipeline step ([#288](https://github.com/lowkeyd3v/arnio/issues/288)) ([a3b7386](https://github.com/lowkeyd3v/arnio/commit/a3b7386e75bc45c9a7fde403ea373334ef528f75))
* add head() and tail() methods to ArFrame ([#565](https://github.com/lowkeyd3v/arnio/issues/565)) ([f254add](https://github.com/lowkeyd3v/arnio/commit/f254add98cecb78404a99b01a9290fe96b2adb53))
* add is_empty convenience property to ArFrame ([37df94d](https://github.com/lowkeyd3v/arnio/commit/37df94d0e4f782fc4510ea8ad179960f51c0fc7d))
* add keep_rows_with_nulls pipeline step ([37dde00](https://github.com/lowkeyd3v/arnio/commit/37dde009d3899e3647183f34209f171afca11f31))
* add normalize_unicode cleaning step ([c8c7c40](https://github.com/lowkeyd3v/arnio/commit/c8c7c40c9172e83d289b25e2e4b797efd78cd26a))
* add numeric quantiles to profile reports ([3934520](https://github.com/lowkeyd3v/arnio/commit/3934520c61abc4fe038b973b8a999bb00520ba74))
* add optional pipeline timing metadata ([7da0bae](https://github.com/lowkeyd3v/arnio/commit/7da0bae28b0cd691781c47f572237dd629bfc2bc)), closes [#162](https://github.com/lowkeyd3v/arnio/issues/162)
* add pandas integration direction ([#399](https://github.com/lowkeyd3v/arnio/issues/399)) ([22f9b58](https://github.com/lowkeyd3v/arnio/commit/22f9b58458383549d97d81ff7828b7a047063525))
* add parse_bool_strings pipeline step ([bc6e53d](https://github.com/lowkeyd3v/arnio/commit/bc6e53d6cbf73c02bcbd81f828a6c085ed928797)), closes [#150](https://github.com/lowkeyd3v/arnio/issues/150)
* add quality sample redaction ([#555](https://github.com/lowkeyd3v/arnio/issues/555)) ([daece46](https://github.com/lowkeyd3v/arnio/commit/daece46037eab5bc924d8e61b4111dc659301ed9))
* add quality score components ([130ad70](https://github.com/lowkeyd3v/arnio/commit/130ad70075757051f1a49c8a0d9d9efb7e5a94de))
* add refactor task issue template ([#334](https://github.com/lowkeyd3v/arnio/issues/334)) ([6690947](https://github.com/lowkeyd3v/arnio/commit/6690947bcada6dc825853036a11ad2310acdd4e4))
* add Regex field validator to schema ([#537](https://github.com/lowkeyd3v/arnio/issues/537)) ([70b1839](https://github.com/lowkeyd3v/arnio/commit/70b18395066c424e143a1a8eb034f3f200d92333))
* add replace_values pipeline step ([#348](https://github.com/lowkeyd3v/arnio/issues/348)) ([02b297c](https://github.com/lowkeyd3v/arnio/commit/02b297c0d60fdb4417e801f2f28db92f50441a4c))
* add round_numeric_columns cleaning helper ([61cd110](https://github.com/lowkeyd3v/arnio/commit/61cd1105e60c6daa38d34ef602f3f9fac28de7ea))
* add safe_divide_columns cleaning step ([80e4a65](https://github.com/lowkeyd3v/arnio/commit/80e4a654d81a1bd95e96b1f5ec83f5f82deff590))
* add sample_size to scan_csv ([9f72698](https://github.com/lowkeyd3v/arnio/commit/9f726987a08b57fc8fa5d6d611e59f6c444a6232))
* add scikit-learn ArnioCleaner transformer ([610a39f](https://github.com/lowkeyd3v/arnio/commit/610a39fe5ab4a02db2ad7f9c3223896cdf263db5))
* add scikit-learn ArnioCleaner transformer ([9788d28](https://github.com/lowkeyd3v/arnio/commit/9788d28fb24ceeca40139ea716996a8f5a330249))
* add standardize_missing_tokens step ([b2bd596](https://github.com/lowkeyd3v/arnio/commit/b2bd596e03c5a3e3143093116ed7f58b557ef84b))
* add string length statistics to quality profile (resolves [#174](https://github.com/lowkeyd3v/arnio/issues/174)) ([#550](https://github.com/lowkeyd3v/arnio/issues/550)) ([98d1bf3](https://github.com/lowkeyd3v/arnio/commit/98d1bf34a9b175610efbb360d034ce0663a8a547))
* add strip_whitespace allocation benchmark ([e2ff584](https://github.com/lowkeyd3v/arnio/commit/e2ff58416125fe1eae4bef4c204cc52fb248fb86))
* add thousands separator parsing ([7ffe50c](https://github.com/lowkeyd3v/arnio/commit/7ffe50cfd669f96cbdc32248fd425d34eb9f1e83))
* add to_pandas copy option ([1746fe1](https://github.com/lowkeyd3v/arnio/commit/1746fe15d5c399d649fff9561a7a02bea147c4de))
* add top_values summary for categorical columns ([f593f94](https://github.com/lowkeyd3v/arnio/commit/f593f94cf331180f29516d1afc217c106a96ad8b))
* add trim_column_names to strip whitespace from column names (Fixes [#138](https://github.com/lowkeyd3v/arnio/issues/138)) ([d4f42c9](https://github.com/lowkeyd3v/arnio/commit/d4f42c9a343f52a74b7da23ae8f830c8687d8fda))
* add trim_headers CSV option ([022460e](https://github.com/lowkeyd3v/arnio/commit/022460e1fa7e9510960a789aa38f835731dec700))
* add validation summary counts ([#444](https://github.com/lowkeyd3v/arnio/issues/444)) ([6575491](https://github.com/lowkeyd3v/arnio/commit/657549174aaca524ce77f169a7e7b3a7b230cba0))
* add ValidationResult.raise_for_errors ([4c34bf6](https://github.com/lowkeyd3v/arnio/commit/4c34bf60f70fa2f5c3183a1598066c4f470003c1))
* add ValidationResult.to_markdown ([168e525](https://github.com/lowkeyd3v/arnio/commit/168e525409ce3a8d60f972dadacfaab01c4cafa8))
* add write_csv via C++ backend ([2a62edc](https://github.com/lowkeyd3v/arnio/commit/2a62edc94108f59fa4894ae88cf266000bb1626d))
* **convert:** preserve DataFrame attrs roundtrip ([4018f27](https://github.com/lowkeyd3v/arnio/commit/4018f27f76dbb021591b4aa6844e2c130887dceb))
* enhance pull request template with media and performance sections ([#336](https://github.com/lowkeyd3v/arnio/issues/336)) ([99b588b](https://github.com/lowkeyd3v/arnio/commit/99b588b62910a68b83abdb39455c0d59de6bba56))
* implement HTML export for DataQualityReport ([#685](https://github.com/lowkeyd3v/arnio/issues/685)) ([6296568](https://github.com/lowkeyd3v/arnio/commit/629656896efb18c33f1949f047738b2dbe48972b))
* initial implementation of C++ core and Python API ([9b9b74c](https://github.com/lowkeyd3v/arnio/commit/9b9b74c86feed2208dfaa26547400321a92e424c))
* initial implementation of C++ core and Python API ([20515df](https://github.com/lowkeyd3v/arnio/commit/20515df85e598a96a26ce3230e46d910fe4357f1))
* phase 1 - normalize_case fix, to_pandas rewrite, Python registry ([344533a](https://github.com/lowkeyd3v/arnio/commit/344533a43a5a9888cab4b5d8eff9bf47f277e8db))
* phase 1 - normalize_case fix, to_pandas rewrite, Python registry ([66b60fb](https://github.com/lowkeyd3v/arnio/commit/66b60fb32dfff3c8841bc3a587960a8a85d9a1f5))
* **quality:** add compare_profiles helper ([a83c860](https://github.com/lowkeyd3v/arnio/commit/a83c860ec5ff05c7d3f33a526550e93f456d2a49)), closes [#185](https://github.com/lowkeyd3v/arnio/issues/185)
* register combine_columns as pipeline step and add test ([beaf402](https://github.com/lowkeyd3v/arnio/commit/beaf4022ac7dc70cb370d387769fc033beb4454d))
* register combine_columns as pipeline step and add test ([c209125](https://github.com/lowkeyd3v/arnio/commit/c2091255286ca66e6b6e54f4f9dcdc304e8fa949))
* **schema:** add cross-field validation rules parameter ([#651](https://github.com/lowkeyd3v/arnio/issues/651)) ([36d0545](https://github.com/lowkeyd3v/arnio/commit/36d054549166542c5401f7a057df25f8a4ab7095)), closes [#196](https://github.com/lowkeyd3v/arnio/issues/196)
* **schema:** add schema diff helper ([fe82072](https://github.com/lowkeyd3v/arnio/commit/fe820726cef88ad6ba702decd46bbe29fbcd8999)), closes [#209](https://github.com/lowkeyd3v/arnio/issues/209)
* **schema:** add warning severity support ([58929c6](https://github.com/lowkeyd3v/arnio/commit/58929c6047d11800e095cd4e3cbfc95d1f379c4b)), closes [#192](https://github.com/lowkeyd3v/arnio/issues/192)
* wrap custom pipeline step errors ([72ddda1](https://github.com/lowkeyd3v/arnio/commit/72ddda1a9ebf7b32619933e7d177f63e4a861ede))


### Bug Fixes

* 52: Remove public set_dtype() and add assert_type_consistency ([4adfc6c](https://github.com/lowkeyd3v/arnio/commit/4adfc6c96456fa0263918fa2ce54cabfcaa2c0c8))
* 52: Remove public set_dtype() and add assert_type_consistency ([9d041c7](https://github.com/lowkeyd3v/arnio/commit/9d041c7ee712262bfce74207df8301ded59ce6bb))
* add YAML validation for GitHub workflow files ([0c666ca](https://github.com/lowkeyd3v/arnio/commit/0c666caa0ce937d70fdffc58dee2e8ba12338412))
* address maintainer review (sklearn constraints, copy behavior, tests) ([37da442](https://github.com/lowkeyd3v/arnio/commit/37da442c4f4bdf8f73911b9bd60fbebcf49568c1))
* allow encoded csv nul handling ([5796a35](https://github.com/lowkeyd3v/arnio/commit/5796a35a32aff5a5d889a72deee255232c527929)), closes [#422](https://github.com/lowkeyd3v/arnio/issues/422)
* apply black formatting and remove trailing blank line ([f5db04f](https://github.com/lowkeyd3v/arnio/commit/f5db04fa1388bd6dc339be732aa1411b613e8fcf))
* **cleaning:** preserve Unicode bytes in normalize_case ([ca6afe6](https://github.com/lowkeyd3v/arnio/commit/ca6afe63397b619ac3f8326ec82bdab31bd9475c)), closes [#26](https://github.com/lowkeyd3v/arnio/issues/26)
* clear errors for unsupported pandas dtypes in from_pandas() ([626a13c](https://github.com/lowkeyd3v/arnio/commit/626a13c8fb3416ff3e077bfec2f333b94309a29b)), closes [#460](https://github.com/lowkeyd3v/arnio/issues/460)
* coerce types in Column::push_back ([525ae75](https://github.com/lowkeyd3v/arnio/commit/525ae75ca88687f5dfb74967ea5512588c3ac06c))
* coerce types in Column::push_back ([ae4d9a0](https://github.com/lowkeyd3v/arnio/commit/ae4d9a0f2d12e9137d381dc0ebdc00dc458d1868))
* correct indentation in test_from_pandas_unsupported_scalar_object_column ([f97bb25](https://github.com/lowkeyd3v/arnio/commit/f97bb253ce4caa41bd5f41a15eda170c6018091a))
* handle empty CSV files with a dedicated error path ([b359173](https://github.com/lowkeyd3v/arnio/commit/b359173f15b5cf6b4cb68b9f04b418d5380c0c44))
* improve nested object error messages in from_pandas ([ca90974](https://github.com/lowkeyd3v/arnio/commit/ca90974cdef4b25824525aa2d4482968054adba2))
* make custom pipeline step registry thread-safe ([2755772](https://github.com/lowkeyd3v/arnio/commit/27557721616a078d4302f9cc7aa2e9f2750b96f5))
* move test_pipeline_clip_numeric inside TestPipeline class ([8ca3bb2](https://github.com/lowkeyd3v/arnio/commit/8ca3bb22afdec2b22056bb64a6324f098324847b))
* normalize title case across punctuation boundaries ([4a9b947](https://github.com/lowkeyd3v/arnio/commit/4a9b947f4045edf61839e70247fcce5b54fe5b1d))
* **pandas:** reject stringified column label collisions ([c3e1d3d](https://github.com/lowkeyd3v/arnio/commit/c3e1d3d006b0cefd6eefdff38659e94dcc05b7b5)), closes [#711](https://github.com/lowkeyd3v/arnio/issues/711)
* **pipeline:** raise TypeError for custom steps returning non-DataFra… ([#687](https://github.com/lowkeyd3v/arnio/issues/687)) ([0008c21](https://github.com/lowkeyd3v/arnio/commit/0008c21bed342e87d2d27e8f2b960716b62542ee))
* preserve 1-based source row numbers in schema validation issues ([5f538fd](https://github.com/lowkeyd3v/arnio/commit/5f538fd2b508b4c791967c8f9b1947387c6467c2))
* preserve 1-based source row numbers in schema validation issues ([3ea089a](https://github.com/lowkeyd3v/arnio/commit/3ea089af93c149c179bbd183c1efde5ff3ebf3cf)), closes [#213](https://github.com/lowkeyd3v/arnio/issues/213)
* preserve column order in scan_csv schema ([a3864f0](https://github.com/lowkeyd3v/arnio/commit/a3864f0640580acdf979d71c18c25ce8c6a9456d))
* preserve Int64 dtype for all-null nullable integer columns in from_pandas roundtrip ([#394](https://github.com/lowkeyd3v/arnio/issues/394)) ([ef726ed](https://github.com/lowkeyd3v/arnio/commit/ef726ed0e1af588c7c0f74a04e02ccfd6a1d688f))
* preserve quoted CSV line endings ([8324322](https://github.com/lowkeyd3v/arnio/commit/8324322d2f32dea78a70dc5fea55e4ccccb4e5f2))
* raise TypeError for nested data in from_pandas ([7389289](https://github.com/lowkeyd3v/arnio/commit/73892893df44f38fa3f0600c26e92965eb029b4a))
* raise TypeError for nested data in from_pandas ([31118b6](https://github.com/lowkeyd3v/arnio/commit/31118b62e39b460381f75644cc23134199a8e950))
* reject duplicate pandas column labels ([5316cf8](https://github.com/lowkeyd3v/arnio/commit/5316cf8b3da3c6d552ffc5910748dad29f69cda0))
* reject impossible schema bounds ([906b286](https://github.com/lowkeyd3v/arnio/commit/906b286ad0bae551bea56746f90fa95135f749ab))
* remove unused import in setup.py ([6590c85](https://github.com/lowkeyd3v/arnio/commit/6590c85d3527fd260566120aaba84eb245e6af78))
* remove unused import in setup.py ([92d3246](https://github.com/lowkeyd3v/arnio/commit/92d32466f7c4a2643827ec38bda616876b4e08a7))
* reorder bool and int type checks in fill_nulls binding ([b8bbebe](https://github.com/lowkeyd3v/arnio/commit/b8bbebe8012f086cb986bf1cdbad5bfdd35ac4f5))
* reorder bool and int type checks in fill_nulls binding ([e3c0907](https://github.com/lowkeyd3v/arnio/commit/e3c0907544f59e8bcee53fbc296576e8bffaccba))
* restore missing imports and fix test failures ([1e700a7](https://github.com/lowkeyd3v/arnio/commit/1e700a78367cff96f4f7bb72736b27f91b8afe73))
* revert unrelated README changes and add non-string type validation ([d5937bf](https://github.com/lowkeyd3v/arnio/commit/d5937bf869840dc440d7e74e8d1de14711f370cb))
* skip numeric cast suggestions for identifier-like columns ([cf687e2](https://github.com/lowkeyd3v/arnio/commit/cf687e2ae83b4cc1c1edef6065920a12fbc7a7ad))
* skip numeric cast suggestions for identifier-like columns ([928398f](https://github.com/lowkeyd3v/arnio/commit/928398fa4eda7fed0f2424e58f442d7781483234))
* strip whitespace from CSV headers ([675452f](https://github.com/lowkeyd3v/arnio/commit/675452f4317e277c25d625efead49bb1682637fa))
* sync version in __init__.py with pyproject.toml ([b159520](https://github.com/lowkeyd3v/arnio/commit/b159520e250e07759b46068df8f9cf52bf7a2851))
* sync version in __init__.py with pyproject.toml ([c3eb21e](https://github.com/lowkeyd3v/arnio/commit/c3eb21e166147dc8069bb699a5cc4c8db4925188))
* use relative import for _arnio_cpp ([fc0c3d6](https://github.com/lowkeyd3v/arnio/commit/fc0c3d6b0e12bbb1f74dc3ba6ada29b551bcf6da))
* use relative import for _arnio_cpp ([adb45aa](https://github.com/lowkeyd3v/arnio/commit/adb45aa3f85069afee5d1778ff1010350dae0e35))
* use typing.Callable instead of callable in pipeline.py type hint ([5d64cb1](https://github.com/lowkeyd3v/arnio/commit/5d64cb1ded77700b72b7f7c6725bf92fd0e9491c))
* use typing.Callable instead of callable in pipeline.py type hint ([661b344](https://github.com/lowkeyd3v/arnio/commit/661b3447c2fe4593ecfee23294d27ace90ce18c0))
* validate file extension and content in read_csv ([7d7582c](https://github.com/lowkeyd3v/arnio/commit/7d7582ca0ff14d4062ce6951a96a09ba27c43a6c))
* validate file extension and content in read_csv ([058b0ee](https://github.com/lowkeyd3v/arnio/commit/058b0ee1a9f83b597c7bd74cafd0a7a06d673c1c))
* validate missing columns in filter_rows ([e0514ef](https://github.com/lowkeyd3v/arnio/commit/e0514ef04fea19fb07fd7373539e1a5019e2763b))
* validate pipeline steps before execution ([#693](https://github.com/lowkeyd3v/arnio/issues/693)) ([d102429](https://github.com/lowkeyd3v/arnio/commit/d102429eced6a92c83cb3d6d1728bf810ea9ba7d))


### Performance Improvements

* add auto-clean memory benchmark ([8bd10f4](https://github.com/lowkeyd3v/arnio/commit/8bd10f4c7301d210a0dcebb64d27006274308705))
* add measurement script for to_pandas conversion overhead ([#556](https://github.com/lowkeyd3v/arnio/issues/556)) ([6c15c53](https://github.com/lowkeyd3v/arnio/commit/6c15c5337ea09cdbe552733e871e09adca704895))
* add process RSS metrics to benchmark ([6206cbd](https://github.com/lowkeyd3v/arnio/commit/6206cbda592705d20877d8a89e2f899025f2f329))
* **cleaning:** implement native clip_numeric without pandas round-trip ([eed031f](https://github.com/lowkeyd3v/arnio/commit/eed031f02c01f48db21f6a7c005dc310cc7d205c)), closes [#657](https://github.com/lowkeyd3v/arnio/issues/657)
* release GIL around long C++ operations ([1100fec](https://github.com/lowkeyd3v/arnio/commit/1100fec21ad05a6288a945af1e88754b7a787280))
* stream transcode and sample rows for scan_csv schema inference ([713aeaa](https://github.com/lowkeyd3v/arnio/commit/713aeaa9ccb380bb68568999edc141e1dc73389b))


### Documentation

* add API reference skeleton ([5ea384d](https://github.com/lowkeyd3v/arnio/commit/5ea384d9341aab15fdbe053ff0388d8f1430cf48))
* add architecture guide, reframe benchmarks, add social preview ([f91e69e](https://github.com/lowkeyd3v/arnio/commit/f91e69e7ffb89adcaa4ed64a5ddd4173e889c045))
* add architecture guide, reframe benchmarks, add social preview ([ab2ddba](https://github.com/lowkeyd3v/arnio/commit/ab2ddbaf422b582b5fc855df71906612936568e9))
* add beginner-friendly auto_clean tutorial with profiling and cleaning workflow  ([#326](https://github.com/lowkeyd3v/arnio/issues/326)) ([b604a0d](https://github.com/lowkeyd3v/arnio/commit/b604a0d067f6603cf6bb5037b5b33b6ff0c19248))
* add CLI roadmap and command examples ([1f4f61d](https://github.com/lowkeyd3v/arnio/commit/1f4f61d5a1c013179ec914931a713a5a833310e5)), closes [#671](https://github.com/lowkeyd3v/arnio/issues/671)
* add comprehensive docstrings to all public Python functions ([3cbe1b3](https://github.com/lowkeyd3v/arnio/commit/3cbe1b35b95678ecc7aa267663dcd998dd74d0f2))
* add contributor glossary ([#308](https://github.com/lowkeyd3v/arnio/issues/308)) ([da52804](https://github.com/lowkeyd3v/arnio/commit/da5280486603e2d630adf33ec8d7162acb9ba0ba))
* add contributors section to README ([70ba51a](https://github.com/lowkeyd3v/arnio/commit/70ba51a6af1922370a0bda70c79ac5ab620f32d3))
* add data quality report examples [#279](https://github.com/lowkeyd3v/arnio/issues/279) ([#295](https://github.com/lowkeyd3v/arnio/issues/295)) ([ca42e87](https://github.com/lowkeyd3v/arnio/commit/ca42e87cf2c596b78286ab3fe4ce8a9c305a6f2a))
* add Discord community links ([#305](https://github.com/lowkeyd3v/arnio/issues/305)) ([64cb4a1](https://github.com/lowkeyd3v/arnio/commit/64cb4a1d871ac7ec8471e28c5386eb8ebfb20ef4))
* add financial CSV cleaning example notebook ([e9fb6f6](https://github.com/lowkeyd3v/arnio/commit/e9fb6f6f793538354160584effd87bf866f85eee))
* add Google Colab install smoke test guide ([99803df](https://github.com/lowkeyd3v/arnio/commit/99803dff307e6934c8d86cf138234bc98caecaa6))
* add gssoc faq ([#309](https://github.com/lowkeyd3v/arnio/issues/309)) ([dc32e56](https://github.com/lowkeyd3v/arnio/commit/dc32e563ba5ff8e2ed2680dec9451d27c65a14e5))
* add interoperability examples ([aa7c7d7](https://github.com/lowkeyd3v/arnio/commit/aa7c7d77d1dcca8a6b7f416ef358a4c6f7ac8edc))
* add issue triage guide for maintainers ([#300](https://github.com/lowkeyd3v/arnio/issues/300)) ([2d6dd6f](https://github.com/lowkeyd3v/arnio/commit/2d6dd6f9c566479757c2146f02e186c1d7d57c2e))
* add language identifiers to unlabeled fenced code blocks (MD040) ([21aad9c](https://github.com/lowkeyd3v/arnio/commit/21aad9c06e1440efa20d377f7842da6afa8d9095))
* add quality and schema architecture flow ([d22fa56](https://github.com/lowkeyd3v/arnio/commit/d22fa56c393c2005c9a351f30ca6132c4ae3c863))
* add release process guide ([#304](https://github.com/lowkeyd3v/arnio/issues/304)) ([f5e1325](https://github.com/lowkeyd3v/arnio/commit/f5e13252889865e24cd464379c9fa3974d2fff03))
* align pandas dtype support documentation with implementation ([#327](https://github.com/lowkeyd3v/arnio/issues/327)) ([badd815](https://github.com/lowkeyd3v/arnio/commit/badd8150a3859ffb1598bdf21f71a8cd2c4c6b0b))
* completely overhaul and beautify README.md ([aef6497](https://github.com/lowkeyd3v/arnio/commit/aef649771e83668d3a47cd11b41b2c230950cd96))
* completely redesign README with flagship-quality presentation ([252988a](https://github.com/lowkeyd3v/arnio/commit/252988a770a0600074734ed44b48e7cbd6763a66))
* completely redesign README with flagship-quality presentation ([5953eb4](https://github.com/lowkeyd3v/arnio/commit/5953eb4a567e9941a9a5ff3c4bc892a19605c737))
* document pandas index conversion behavior ([#407](https://github.com/lowkeyd3v/arnio/issues/407)) ([327b650](https://github.com/lowkeyd3v/arnio/commit/327b650bb40b8ba902c5b0dc903b98d5f3e1172e))
* document write_csv validation behavior ([4588666](https://github.com/lowkeyd3v/arnio/commit/45886660c5087d80ab2aeb39ebd64562836805e8)), closes [#664](https://github.com/lowkeyd3v/arnio/issues/664)
* duplicated code ([62401a1](https://github.com/lowkeyd3v/arnio/commit/62401a1418acb149b74697495467fd05e22fa14f))
* enforce conventional commits in contributor guidelines ([d98f6cf](https://github.com/lowkeyd3v/arnio/commit/d98f6cf208f8acc5d34dc0bee280f28a64cc1dbe))
* expand pipeline execution and cleaning module architecture ([17e51af](https://github.com/lowkeyd3v/arnio/commit/17e51af852fa0c3c306b9d1581752eddafc0fe4b))
* fix non-sequential roadmap versions ([#107](https://github.com/lowkeyd3v/arnio/issues/107)) ([db3b8e4](https://github.com/lowkeyd3v/arnio/commit/db3b8e47fc721ad899df0b6239bc706824d168a5))
* implement Phase 2 contributor infrastructure and issue templates ([ae8d377](https://github.com/lowkeyd3v/arnio/commit/ae8d377b6bacf8623ff0d1a185c27217f6623d14))
* improve quickstart wording ([a3f37d9](https://github.com/lowkeyd3v/arnio/commit/a3f37d94146f5f1b3939b0962236242312dadcac))
* include pandas dtype fix in 1.11.2 notes ([2385b3a](https://github.com/lowkeyd3v/arnio/commit/2385b3acb3fe92b11c266cd2321ad2d662a76472))
* premium landing page overhaul for README ([693e5e4](https://github.com/lowkeyd3v/arnio/commit/693e5e4be6d67cf45e903e4a2dcd111bacb48959))
* prepare repository for GSSoC contributors ([#289](https://github.com/lowkeyd3v/arnio/issues/289)) ([d270812](https://github.com/lowkeyd3v/arnio/commit/d2708126a20d6e12be75a438d631f84aa802e13f))
* remove duplicated code ([0e215f9](https://github.com/lowkeyd3v/arnio/commit/0e215f9080abbe77183f51a9a1b07e90d60bc54f))
* remove large Discord badge from README ([#307](https://github.com/lowkeyd3v/arnio/issues/307)) ([1f0ff3a](https://github.com/lowkeyd3v/arnio/commit/1f0ff3ab15d111344cc9c6281226ef6361f919f9))
* replace ASCII architecture diagram with Mermaid flowchart ([abede39](https://github.com/lowkeyd3v/arnio/commit/abede392dfd11ac909d273c90cfc01463522004b))
* rewrite README with differentiation, performance benchmarks, and intro gif ([14b9820](https://github.com/lowkeyd3v/arnio/commit/14b982055e14854f0542e998e5da039b50c7b6f9))


### Miscellaneous Chores

* **main:** release 1.10.0 ([2bb83b2](https://github.com/lowkeyd3v/arnio/commit/2bb83b20d766a64ff219c067ed1828fbf582e99d))
* **main:** release 1.9.1 ([ab6a2d6](https://github.com/lowkeyd3v/arnio/commit/ab6a2d67a1ecfddd37ffef9488aa7dbdafc40af6))

## [1.14.0](https://github.com/im-anishraj/arnio/compare/v1.13.0...v1.14.0) (2026-05-18)


### Features

* add parse_bool_strings pipeline step ([bc6e53d](https://github.com/im-anishraj/arnio/commit/bc6e53d6cbf73c02bcbd81f828a6c085ed928797)), closes [#150](https://github.com/im-anishraj/arnio/issues/150)


### Documentation

* add interoperability examples ([aa7c7d7](https://github.com/im-anishraj/arnio/commit/aa7c7d77d1dcca8a6b7f416ef358a4c6f7ac8edc))

## [1.13.0](https://github.com/im-anishraj/arnio/compare/v1.12.1...v1.13.0) (2026-05-18)


### Features

* add benchmark regression reporting ([#554](https://github.com/im-anishraj/arnio/issues/554)) ([83b9ee5](https://github.com/im-anishraj/arnio/commit/83b9ee5c8cf75477ebb476f1fb3f13654eceab3a))
* add quality sample redaction ([#555](https://github.com/im-anishraj/arnio/issues/555)) ([daece46](https://github.com/im-anishraj/arnio/commit/daece46037eab5bc924d8e61b4111dc659301ed9))
* add Regex field validator to schema ([#537](https://github.com/im-anishraj/arnio/issues/537)) ([70b1839](https://github.com/im-anishraj/arnio/commit/70b18395066c424e143a1a8eb034f3f200d92333))
* add string length statistics to quality profile (resolves [#174](https://github.com/im-anishraj/arnio/issues/174)) ([#550](https://github.com/im-anishraj/arnio/issues/550)) ([98d1bf3](https://github.com/im-anishraj/arnio/commit/98d1bf34a9b175610efbb360d034ce0663a8a547))

## [1.12.1](https://github.com/im-anishraj/arnio/compare/v1.12.0...v1.12.1) (2026-05-18)


### Bug Fixes

* make custom pipeline step registry thread-safe ([2755772](https://github.com/im-anishraj/arnio/commit/27557721616a078d4302f9cc7aa2e9f2750b96f5))


### Performance Improvements

* release GIL around long C++ operations ([1100fec](https://github.com/im-anishraj/arnio/commit/1100fec21ad05a6288a945af1e88754b7a787280))

## [1.12.0](https://github.com/im-anishraj/arnio/compare/v1.11.3...v1.12.0) (2026-05-17)


### Features

* add strip_whitespace allocation benchmark ([e2ff584](https://github.com/im-anishraj/arnio/commit/e2ff58416125fe1eae4bef4c204cc52fb248fb86))


### Documentation

* replace ASCII architecture diagram with Mermaid flowchart ([abede39](https://github.com/im-anishraj/arnio/commit/abede392dfd11ac909d273c90cfc01463522004b))

## [1.11.3](https://github.com/im-anishraj/arnio/compare/v1.11.2...v1.11.3) (2026-05-17)


### Documentation

* add API reference skeleton ([5ea384d](https://github.com/im-anishraj/arnio/commit/5ea384d9341aab15fdbe053ff0388d8f1430cf48))

## [1.11.2](https://github.com/im-anishraj/arnio/compare/v1.11.1...v1.11.2) (2026-05-17)


### Bug Fixes

* raise clear errors for unsupported pandas dtypes in from_pandas ([1791e4f](https://github.com/im-anishraj/arnio/commit/1791e4f05242841e7878fd8c03a185bb01c48ae1))
* preserve 1-based source row numbers in schema validation issues ([5f538fd](https://github.com/im-anishraj/arnio/commit/5f538fd2b508b4c791967c8f9b1947387c6467c2))

## [1.11.1](https://github.com/im-anishraj/arnio/compare/v1.11.0...v1.11.1) (2026-05-17)


### Bug Fixes

* skip numeric cast suggestions for identifier-like columns ([cf687e2](https://github.com/im-anishraj/arnio/commit/cf687e2ae83b4cc1c1edef6065920a12fbc7a7ad))

## [1.11.0](https://github.com/im-anishraj/arnio/compare/v1.10.0...v1.11.0) (2026-05-17)


### Features

* add scikit-learn ArnioCleaner transformer ([610a39f](https://github.com/im-anishraj/arnio/commit/610a39fe5ab4a02db2ad7f9c3223896cdf263db5))
* register combine_columns as pipeline step and add test ([beaf402](https://github.com/im-anishraj/arnio/commit/beaf4022ac7dc70cb370d387769fc033beb4454d))

## [1.10.0](https://github.com/im-anishraj/arnio/compare/v1.9.1...v1.10.0) (2026-05-17)


### Features

* add DateTime schema field ([05c26be](https://github.com/im-anishraj/arnio/commit/05c26bebf1cf79bbdbb98157dba1618c61abd08e))
* add normalize_unicode cleaning step ([c8c7c40](https://github.com/im-anishraj/arnio/commit/c8c7c40c9172e83d289b25e2e4b797efd78cd26a))
* add top_values summary for categorical columns ([f593f94](https://github.com/im-anishraj/arnio/commit/f593f94cf331180f29516d1afc217c106a96ad8b))


### Performance Improvements

* add process RSS metrics to benchmark ([6206cbd](https://github.com/im-anishraj/arnio/commit/6206cbda592705d20877d8a89e2f899025f2f329))


### Documentation

* add financial CSV cleaning example notebook ([e9fb6f6](https://github.com/im-anishraj/arnio/commit/e9fb6f6f793538354160584effd87bf866f85eee))

## [1.9.1](https://github.com/im-anishraj/arnio/compare/v1.9.0...v1.9.1) (2026-05-17)


### Performance Improvements

* stream transcode and sample rows for scan_csv schema inference ([713aeaa](https://github.com/im-anishraj/arnio/commit/713aeaa9ccb380bb68568999edc141e1dc73389b))

## [1.9.0](https://github.com/im-anishraj/arnio/compare/v1.8.0...v1.9.0) (2026-05-17)


### Features

* add composite uniqueness validation support ([#495](https://github.com/im-anishraj/arnio/issues/495)) ([8b11e19](https://github.com/im-anishraj/arnio/commit/8b11e19180b97fde1c380857e702d78dc7df8fc8))
* add CountryCode schema validator ([#487](https://github.com/im-anishraj/arnio/issues/487)) ([14a77e5](https://github.com/im-anishraj/arnio/commit/14a77e532409bffc0fdef85fbbbaaa798782dde7))
* add replace_values pipeline step ([#348](https://github.com/im-anishraj/arnio/issues/348)) ([02b297c](https://github.com/im-anishraj/arnio/commit/02b297c0d60fdb4417e801f2f28db92f50441a4c))


### Documentation

* document pandas index conversion behavior ([#407](https://github.com/im-anishraj/arnio/issues/407)) ([327b650](https://github.com/im-anishraj/arnio/commit/327b650bb40b8ba902c5b0dc903b98d5f3e1172e))

## [1.8.0](https://github.com/im-anishraj/arnio/compare/v1.7.0...v1.8.0) (2026-05-17)


### Features

* add ArFrame.select_dtypes for type-based column selection ([7899541](https://github.com/im-anishraj/arnio/commit/7899541113aad0f300decc08b94f285b920f3008))
* add trim_column_names cleaning primitive and pipeline step ([d064335](https://github.com/im-anishraj/arnio/commit/d0643355f1f626a4ee2a4264aea67e316971df76))


### Bug Fixes

* reject impossible schema bounds ([906b286](https://github.com/im-anishraj/arnio/commit/906b286ad0bae551bea56746f90fa95135f749ab))

## [1.7.0](https://github.com/im-anishraj/arnio/compare/v1.6.2...v1.7.0) (2026-05-17)


### Features

* add keep_rows_with_nulls pipeline step ([37dde00](https://github.com/im-anishraj/arnio/commit/37dde009d3899e3647183f34209f171afca11f31))


### Bug Fixes

* add YAML validation for GitHub workflow files ([0c666ca](https://github.com/im-anishraj/arnio/commit/0c666caa0ce937d70fdffc58dee2e8ba12338412))


### Performance Improvements

* add auto-clean memory benchmark ([8bd10f4](https://github.com/im-anishraj/arnio/commit/8bd10f4c7301d210a0dcebb64d27006274308705))

## [1.6.2](https://github.com/im-anishraj/arnio/compare/v1.6.1...v1.6.2) (2026-05-17)


### Documentation

* improve quickstart wording ([a3f37d9](https://github.com/im-anishraj/arnio/commit/a3f37d94146f5f1b3939b0962236242312dadcac))

## [1.6.1](https://github.com/im-anishraj/arnio/compare/v1.6.0...v1.6.1) (2026-05-16)


### Bug Fixes

* preserve column order in scan_csv schema ([a3864f0](https://github.com/im-anishraj/arnio/commit/a3864f0640580acdf979d71c18c25ce8c6a9456d))
* validate missing columns in filter_rows ([e0514ef](https://github.com/im-anishraj/arnio/commit/e0514ef04fea19fb07fd7373539e1a5019e2763b))

## [1.6.0](https://github.com/im-anishraj/arnio/compare/v1.5.1...v1.6.0) (2026-05-16)


### Features

* add to_pandas copy option ([1746fe1](https://github.com/im-anishraj/arnio/commit/1746fe15d5c399d649fff9561a7a02bea147c4de))

## [1.5.1](https://github.com/im-anishraj/arnio/compare/v1.5.0...v1.5.1) (2026-05-16)


### Bug Fixes

* normalize title case across punctuation boundaries ([4a9b947](https://github.com/im-anishraj/arnio/commit/4a9b947f4045edf61839e70247fcce5b54fe5b1d))

## [1.5.0](https://github.com/im-anishraj/arnio/compare/v1.4.0...v1.5.0) (2026-05-16)


### Features

* add is_empty convenience property to ArFrame ([37df94d](https://github.com/im-anishraj/arnio/commit/37df94d0e4f782fc4510ea8ad179960f51c0fc7d))
* add validation summary counts ([#444](https://github.com/im-anishraj/arnio/issues/444)) ([6575491](https://github.com/im-anishraj/arnio/commit/657549174aaca524ce77f169a7e7b3a7b230cba0))


### Bug Fixes

* allow encoded csv nul handling ([5796a35](https://github.com/im-anishraj/arnio/commit/5796a35a32aff5a5d889a72deee255232c527929)), closes [#422](https://github.com/im-anishraj/arnio/issues/422)

## [1.4.0](https://github.com/im-anishraj/arnio/compare/v1.3.1...v1.4.0) (2026-05-16)


### Features

* add bounded profiling sample_size validation ([1e31269](https://github.com/im-anishraj/arnio/commit/1e3126986bdc21e128fc734a71a77aa7f242441a))

## [1.3.1](https://github.com/im-anishraj/arnio/compare/v1.3.0...v1.3.1) (2026-05-16)


### Bug Fixes

* handle empty CSV files with a dedicated error path ([b359173](https://github.com/im-anishraj/arnio/commit/b359173f15b5cf6b4cb68b9f04b418d5380c0c44))

## [1.3.0](https://github.com/im-anishraj/arnio/compare/v1.2.0...v1.3.0) (2026-05-15)


### Features

* add column existence validation helper ([517d1e0](https://github.com/im-anishraj/arnio/commit/517d1e07d3b19252027ecdfac23d17b19e0aa793))
* add pandas integration direction ([#399](https://github.com/im-anishraj/arnio/issues/399)) ([22f9b58](https://github.com/im-anishraj/arnio/commit/22f9b58458383549d97d81ff7828b7a047063525))
* **convert:** preserve DataFrame attrs roundtrip ([4018f27](https://github.com/im-anishraj/arnio/commit/4018f27f76dbb021591b4aa6844e2c130887dceb))


### Bug Fixes

* preserve Int64 dtype for all-null nullable integer columns in from_pandas roundtrip ([#394](https://github.com/im-anishraj/arnio/issues/394)) ([ef726ed](https://github.com/im-anishraj/arnio/commit/ef726ed0e1af588c7c0f74a04e02ccfd6a1d688f))


### Documentation

* add quality and schema architecture flow ([d22fa56](https://github.com/im-anishraj/arnio/commit/d22fa56c393c2005c9a351f30ca6132c4ae3c863))

## [1.2.0](https://github.com/im-anishraj/arnio/compare/v1.1.1...v1.2.0) (2026-05-15)


### Features

* add ArFrame preview method ([814102e](https://github.com/im-anishraj/arnio/commit/814102e35b153cf75b3a759a5e33867edfe03321))
* add ArFrame select_columns helper ([fff406d](https://github.com/im-anishraj/arnio/commit/fff406d9a10943cb6f2bd76d32240933da90ed51))
* add clip_numeric cleaning helper ([4022449](https://github.com/im-anishraj/arnio/commit/4022449c7bbe5e31c94e756ff29a36b4c274a232))
* add drop constant columns ([#357](https://github.com/im-anishraj/arnio/issues/357)) ([3e13d3d](https://github.com/im-anishraj/arnio/commit/3e13d3d576add9fd8113cdf185ca08e61e75c4ee))
* add filter_rows pipeline step ([#288](https://github.com/im-anishraj/arnio/issues/288)) ([a3b7386](https://github.com/im-anishraj/arnio/commit/a3b7386e75bc45c9a7fde403ea373334ef528f75))
* add refactor task issue template ([#334](https://github.com/im-anishraj/arnio/issues/334)) ([6690947](https://github.com/im-anishraj/arnio/commit/6690947bcada6dc825853036a11ad2310acdd4e4))
* add round_numeric_columns cleaning helper ([61cd110](https://github.com/im-anishraj/arnio/commit/61cd1105e60c6daa38d34ef602f3f9fac28de7ea))
* add safe_divide_columns cleaning step ([80e4a65](https://github.com/im-anishraj/arnio/commit/80e4a654d81a1bd95e96b1f5ec83f5f82deff590))
* add trim_headers CSV option ([022460e](https://github.com/im-anishraj/arnio/commit/022460e1fa7e9510960a789aa38f835731dec700))
* add ValidationResult.to_markdown ([168e525](https://github.com/im-anishraj/arnio/commit/168e525409ce3a8d60f972dadacfaab01c4cafa8))
* enhance pull request template with media and performance sections ([#336](https://github.com/im-anishraj/arnio/issues/336)) ([99b588b](https://github.com/im-anishraj/arnio/commit/99b588b62910a68b83abdb39455c0d59de6bba56))


### Bug Fixes

* improve nested object error messages in from_pandas ([ca90974](https://github.com/im-anishraj/arnio/commit/ca90974cdef4b25824525aa2d4482968054adba2))


### Documentation

* add beginner-friendly auto_clean tutorial with profiling and cleaning workflow  ([#326](https://github.com/im-anishraj/arnio/issues/326)) ([b604a0d](https://github.com/im-anishraj/arnio/commit/b604a0d067f6603cf6bb5037b5b33b6ff0c19248))
* add contributor glossary ([#308](https://github.com/im-anishraj/arnio/issues/308)) ([da52804](https://github.com/im-anishraj/arnio/commit/da5280486603e2d630adf33ec8d7162acb9ba0ba))
* add data quality report examples [#279](https://github.com/im-anishraj/arnio/issues/279) ([#295](https://github.com/im-anishraj/arnio/issues/295)) ([ca42e87](https://github.com/im-anishraj/arnio/commit/ca42e87cf2c596b78286ab3fe4ce8a9c305a6f2a))
* add Discord community links ([#305](https://github.com/im-anishraj/arnio/issues/305)) ([64cb4a1](https://github.com/im-anishraj/arnio/commit/64cb4a1d871ac7ec8471e28c5386eb8ebfb20ef4))
* add gssoc faq ([#309](https://github.com/im-anishraj/arnio/issues/309)) ([dc32e56](https://github.com/im-anishraj/arnio/commit/dc32e563ba5ff8e2ed2680dec9451d27c65a14e5))
* add issue triage guide for maintainers ([#300](https://github.com/im-anishraj/arnio/issues/300)) ([2d6dd6f](https://github.com/im-anishraj/arnio/commit/2d6dd6f9c566479757c2146f02e186c1d7d57c2e))
* add release process guide ([#304](https://github.com/im-anishraj/arnio/issues/304)) ([f5e1325](https://github.com/im-anishraj/arnio/commit/f5e13252889865e24cd464379c9fa3974d2fff03))
* align pandas dtype support documentation with implementation ([#327](https://github.com/im-anishraj/arnio/issues/327)) ([badd815](https://github.com/im-anishraj/arnio/commit/badd8150a3859ffb1598bdf21f71a8cd2c4c6b0b))
* fix non-sequential roadmap versions ([#107](https://github.com/im-anishraj/arnio/issues/107)) ([db3b8e4](https://github.com/im-anishraj/arnio/commit/db3b8e47fc721ad899df0b6239bc706824d168a5))
* remove large Discord badge from README ([#307](https://github.com/im-anishraj/arnio/issues/307)) ([1f0ff3a](https://github.com/im-anishraj/arnio/commit/1f0ff3ab15d111344cc9c6281226ef6361f919f9))

## [1.1.1](https://github.com/im-anishraj/arnio/compare/v1.1.0...v1.1.1) (2026-05-14)


### Documentation

* prepare repository for GSSoC contributors ([#289](https://github.com/im-anishraj/arnio/issues/289)) ([d270812](https://github.com/im-anishraj/arnio/commit/d2708126a20d6e12be75a438d631f84aa802e13f))

## [1.1.0](https://github.com/im-anishraj/arnio/compare/v1.0.2...v1.1.0) (2026-05-14)


### Features

* add data quality engine ([6053ab9](https://github.com/im-anishraj/arnio/commit/6053ab93fa29b706a20f5fd8d905f046fedb36c5))
* add data quality engine ([f8abb2f](https://github.com/im-anishraj/arnio/commit/f8abb2f8202e9d1fa394a2e1e97576f003d113b0))

## [1.0.2](https://github.com/im-anishraj/arnio/compare/v1.0.1...v1.0.2) (2026-05-10)


### Documentation

* add language identifiers to unlabeled fenced code blocks (MD040) ([21aad9c](https://github.com/im-anishraj/arnio/commit/21aad9c06e1440efa20d377f7842da6afa8d9095))
* completely redesign README with flagship-quality presentation ([252988a](https://github.com/im-anishraj/arnio/commit/252988a770a0600074734ed44b48e7cbd6763a66))
* completely redesign README with flagship-quality presentation ([5953eb4](https://github.com/im-anishraj/arnio/commit/5953eb4a567e9941a9a5ff3c4bc892a19605c737))

## [1.0.1](https://github.com/im-anishraj/arnio/compare/v1.0.0...v1.0.1) (2026-05-09)


### Documentation

* add architecture guide, reframe benchmarks, add social preview ([f91e69e](https://github.com/im-anishraj/arnio/commit/f91e69e7ffb89adcaa4ed64a5ddd4173e889c045))
* add architecture guide, reframe benchmarks, add social preview ([ab2ddba](https://github.com/im-anishraj/arnio/commit/ab2ddbaf422b582b5fc855df71906612936568e9))
* add comprehensive docstrings to all public Python functions ([3cbe1b3](https://github.com/im-anishraj/arnio/commit/3cbe1b35b95678ecc7aa267663dcd998dd74d0f2))
* duplicated code ([62401a1](https://github.com/im-anishraj/arnio/commit/62401a1418acb149b74697495467fd05e22fa14f))
* enforce conventional commits in contributor guidelines ([d98f6cf](https://github.com/im-anishraj/arnio/commit/d98f6cf208f8acc5d34dc0bee280f28a64cc1dbe))
* remove duplicated code ([0e215f9](https://github.com/im-anishraj/arnio/commit/0e215f9080abbe77183f51a9a1b07e90d60bc54f))

## [Unreleased]
### Fixed
- Fixed type consistency check in Column (#52)

## [1.0.0] - 2026-05-08
### Added
- **Cross-Platform Wheels**: Full `cibuildwheel` automation delivering pre-compiled native wheels for Windows, Linux, and macOS (Intel & Apple Silicon).
- **Google Colab Compatibility**: Linux wheels are now fully `manylinux` compliant, allowing `pip install arnio` to work out-of-the-box on Colab and Ubuntu.
- **Production-Grade Packaging**: Resolved `ModuleNotFoundError` by removing double-nesting issues in `scikit-build-core` config.
- **CI/CD Excellence**: Fully automated PyPI publishing pipeline via Trusted Publishing with integrated source distributions (`sdist`).
- **Stable API**: Officially marked `arnio` as stable for production workloads with "Development Status :: 5 - Production/Stable".

### Fixed
- Migrated from `FetchContent` to `find_package(pybind11)` for faster, offline, and more robust cross-platform builds.
- Refactored `cibuildwheel` configuration entirely into `pyproject.toml` for standard and declarative packaging.

## [0.1.3] - 2026-05-06
### Fixed
- `normalize_case()` now accepts `case_type` kwarg as documented in README
  (previously accepted `case=`, causing TypeError for all README users)
- `to_pandas()` completely rewritten using zero-copy NumPy buffer interface —
  eliminates O(rows × cols) pybind11 boundary crossings, restoring actual 
  performance advantage over pandas
- `from_pandas()` implemented with correct null handling and round-trip fidelity

### Added
- `ar.register_step(name, fn)` — register pure-Python pipeline steps without C++
- `arnio.exceptions` module with `ArnioError`, `UnknownStepError`, `CsvReadError`, 
  `TypeCastError` — replaces opaque C++ errors with actionable messages
- `arnio.__version__` now available programmatically
- `benchmarks/generate_data.py` — deterministic 1M row test dataset generator
- `benchmarks/benchmark_vs_pandas.py` — reproducible end-to-end benchmark

### Fixed (Internal)
- CI now verifies compilation on Ubuntu and Windows across Python 3.9–3.12

## [0.1.2] - 2026-05-03
### Fixed
- Stability improvements and initial PyPI release
