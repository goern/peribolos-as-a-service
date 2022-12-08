# [1.3.0](https://github.com/operate-first/peribolos-as-a-service/compare/v1.2.1...v1.3.0) (2022-12-08)


### Bug Fixes

* **deps:** pin dependency lru-cache to v7.13.1 ([#187](https://github.com/operate-first/peribolos-as-a-service/issues/187)) ([d0c1358](https://github.com/operate-first/peribolos-as-a-service/commit/d0c135822d9cf2f23ce113280cba676c7dc21168))
* **deps:** update all non-major dependencies ([#195](https://github.com/operate-first/peribolos-as-a-service/issues/195)) ([5f0ca45](https://github.com/operate-first/peribolos-as-a-service/commit/5f0ca45bc3be405bfb8c8fd6a47868a74f4e6ee3))
* Fix how metric labels are calculated ([3b51edc](https://github.com/operate-first/peribolos-as-a-service/commit/3b51edcd8fbccf89eff02ae3762e8504d7ac5b2b))
* Limit push events to .github repo only ([#175](https://github.com/operate-first/peribolos-as-a-service/issues/175)) ([d9f1b5e](https://github.com/operate-first/peribolos-as-a-service/commit/d9f1b5e3e3605fea883857f76ce3a11a514c6d60))
* Renew credentials on check retry ([#211](https://github.com/operate-first/peribolos-as-a-service/issues/211)) ([3c83e2b](https://github.com/operate-first/peribolos-as-a-service/commit/3c83e2b46be8900eda4fc6b21f9285d23ca8bbe2))
* set --require-self to false on peribolos-run task ([#210](https://github.com/operate-first/peribolos-as-a-service/issues/210)) ([c19ed99](https://github.com/operate-first/peribolos-as-a-service/commit/c19ed99b9563fb3a1f392a69e42540c9cab25f02))


### Features

* Add basic prometheus alerts ([#177](https://github.com/operate-first/peribolos-as-a-service/issues/177)) ([80e1129](https://github.com/operate-first/peribolos-as-a-service/commit/80e11291c2e539db43a8afaf2125fe4fd566fb92))
* Add OCP link to check ([#183](https://github.com/operate-first/peribolos-as-a-service/issues/183)) ([ba545cc](https://github.com/operate-first/peribolos-as-a-service/commit/ba545cc72769cf6e4742b3d2348497d086e02890))
* Update tasks for peribolos upstream change ([#163](https://github.com/operate-first/peribolos-as-a-service/issues/163)) ([b443b7c](https://github.com/operate-first/peribolos-as-a-service/commit/b443b7c091bb8befde56f674891f7b3b31328f2d))

## [1.2.1](https://github.com/operate-first/peribolos-as-a-service/compare/v1.2.0...v1.2.1) (2022-07-11)


### Bug Fixes

* **deps:** update all non-major dependencies ([#157](https://github.com/operate-first/peribolos-as-a-service/issues/157)) ([561f55c](https://github.com/operate-first/peribolos-as-a-service/commit/561f55c38a988ab8aa5c20ce412b2dc893a01207))
* wrapOperationWithMetrics status label ([#168](https://github.com/operate-first/peribolos-as-a-service/issues/168)) ([6cae69e](https://github.com/operate-first/peribolos-as-a-service/commit/6cae69eead70eb6781e6de158ee10c981a3f55ff))

# [1.2.0](https://github.com/operate-first/peribolos-as-a-service/compare/v1.1.0...v1.2.0) (2022-07-07)


### Bug Fixes

* **tasks:** Reference the correct secret ([abb2957](https://github.com/operate-first/peribolos-as-a-service/commit/abb2957cd2b4104af54f923089b780eac20b523b))


### Features

* **controller:** Create GitHub check for taskRuns ([#146](https://github.com/operate-first/peribolos-as-a-service/issues/146)) ([24b25e9](https://github.com/operate-first/peribolos-as-a-service/commit/24b25e9305c24b0bf8e7df2bf6914a45de8a10c2))


### Reverts

* Reset dev overlay to base ([3b503ec](https://github.com/operate-first/peribolos-as-a-service/commit/3b503ec0f4e3023f25d02e3b8af558c41ed543fa))

# [1.1.0](https://github.com/operate-first/peribolos-as-a-service/compare/v1.0.1...v1.1.0) (2022-06-30)


### Features

* Relocate Probot repositories to Operate First ([48d3a82](https://github.com/operate-first/peribolos-as-a-service/commit/48d3a82b800bce52c4703c6bf65053c1edc4f794))

## [1.0.1](https://github.com/open-services-group/peribolos-as-a-service/compare/v1.0.0...v1.0.1) (2022-06-21)


### Bug Fixes

* **controller:** Role to allow secret deletion ([6974335](https://github.com/open-services-group/peribolos-as-a-service/commit/6974335360b77f5a1ea93194cc4809d1fa7d074c))
* **deps:** pin dependency prom-client to 14.0.1 ([14e519e](https://github.com/open-services-group/peribolos-as-a-service/commit/14e519e8ba0630221d89a4cc7475efed77ee3fcd))
* Manifests nameprefix not propagated to route's service selector ([17b9ff3](https://github.com/open-services-group/peribolos-as-a-service/commit/17b9ff363d3ead2e2de1e9d5294c1e1d2f15b7df))
* **peribolos:** Swap base image so we get SSL ([76bc073](https://github.com/open-services-group/peribolos-as-a-service/commit/76bc07325d2f7864936f07782de022157fa4b037))
* Probot on kube doesn't work in prod builds ([e25ce57](https://github.com/open-services-group/peribolos-as-a-service/commit/e25ce5708cbe284293c9861651f9e20fe733280a))
* **tasks:** Dump config controller secret reference ([2bf061a](https://github.com/open-services-group/peribolos-as-a-service/commit/2bf061a8870d77c61a9d5dcf31fe6403ca37d3e3))
* **tasks:** Proper config propagation ([9a222b6](https://github.com/open-services-group/peribolos-as-a-service/commit/9a222b6e86ffdeb22f984ed7c209448e835a9faa))

# 1.0.0 (2022-05-05)


### Bug Fixes

* Cleanup some labels in deployment manifests ([214ceb5](https://github.com/open-services-group/peribolos-as-a-service/commit/214ceb59ce617261f7452760c1983d0f8bb0d038))
* Deployment CPU request is wrong format ([ff83df1](https://github.com/open-services-group/peribolos-as-a-service/commit/ff83df1d206a7da7afe3129d1aab2deba0948bc7))
* Deployment CPU request is wrong format [2] ([3294940](https://github.com/open-services-group/peribolos-as-a-service/commit/3294940e62d2f6c9ded0447ded3ab8e65de60c40))
* **deps:** pin dependencies ([a7b8922](https://github.com/open-services-group/peribolos-as-a-service/commit/a7b892219d6dee74b54b2fb2300e38cc9f4978d9))
* **deps:** update dependency probot to v12 ([b73978a](https://github.com/open-services-group/peribolos-as-a-service/commit/b73978a62c56165fbe6aef9f061fa7ed9f3ba92c))
* Fix namespace variable name in push event ([cd9eca6](https://github.com/open-services-group/peribolos-as-a-service/commit/cd9eca6f40c84e2dea73c5278d689cf94e5c18a5))
* type issues with new @octokit/webhooks version ([db6690f](https://github.com/open-services-group/peribolos-as-a-service/commit/db6690fb1dac849d8b4856782e7593da076128a9))
* Use https route ([3891f59](https://github.com/open-services-group/peribolos-as-a-service/commit/3891f597152bbc0c2093925958abacd5ec907449))


### Features

* Add push event controller ([508d39c](https://github.com/open-services-group/peribolos-as-a-service/commit/508d39cfe4dc8b7c88ab9e6775e16084bdf8a594))
* Add script to build an image ([01128d3](https://github.com/open-services-group/peribolos-as-a-service/commit/01128d3646841a1264bbba654db10e35907c987b))
* **architecture:** Initial architecture draft ([fab17cb](https://github.com/open-services-group/peribolos-as-a-service/commit/fab17cbeb13e9ec6d95ffed4b7952089558583cd))
* Bootstrap the repostiory for a Github App controller ([bd8eb79](https://github.com/open-services-group/peribolos-as-a-service/commit/bd8eb7960a74bb8079c83f318817e6ef159cce80))
* Change AICOE-CI from Docker strategy to source ([aa67aa1](https://github.com/open-services-group/peribolos-as-a-service/commit/aa67aa187c379e57b705871e97c4748938c00da3))
* Handle push on .github repository ([b978d3e](https://github.com/open-services-group/peribolos-as-a-service/commit/b978d3e3bbc5a08325730fd0ecde8feecb4e9d4d))
* Initial commit ([5eb5475](https://github.com/open-services-group/peribolos-as-a-service/commit/5eb5475814a81e95655200f8462fd9fbd5c1dcf5))
* Update token on push ([bb0be49](https://github.com/open-services-group/peribolos-as-a-service/commit/bb0be4949ae3eff128b5b7b522a11d7a45c54a67))
* Use custom host for peribolos ([d321069](https://github.com/open-services-group/peribolos-as-a-service/commit/d321069fa27598d78321f1dd8cada228ac442c47))
