## Debug Log

```log
DEBUG: checkOnboarding() (repository=RahulGautamSingh-testing/repro-21768)
DEBUG: isOnboarded() (repository=RahulGautamSingh-testing/repro-21768)
DEBUG: findPr(renovate/configure, Configure Renovate, !open) (repository=RahulGautamSingh-testing/repro-21768)
DEBUG: getPrList success (repository=RahulGautamSingh-testing/repro-21768)
       "pullsTotal": 1,
       "requestsTotal": 1,
       "apiQuotaAffected": true
DEBUG: Found PR #1 (repository=RahulGautamSingh-testing/repro-21768)
DEBUG: Checking cached config file name (repository=RahulGautamSingh-testing/repro-21768)
DEBUG: GET https://api.github.com/repos/RahulGautamSingh-testing/repro-21768/contents/renovate.json = (code=ERR_N...pro-21768)
DEBUG: Existing config file no longer exists (repository=RahulGautamSingh-testing/repro-21768)
DEBUG: findFile(renovate.json) (repository=RahulGautamSingh-testing/repro-21768)
DEBUG: Performing blobless clone (repository=RahulGautamSingh-testing/repro-21768)
...
DEBUG: findFile(renovate.json5) (repository=RahulGautamSingh-testing/repro-21768)
...
DEBUG: config file not found (repository=RahulGautamSingh-testing/repro-21768)
DEBUG: Found closed onboarding PR (repository=RahulGautamSingh-testing/repro-21768)
DEBUG: Repo is not onboarded and no merged PRs exist (repository=RahulGautamSingh-testing/repro-21768)
DEBUG: Getting comments for #1 (repository=RahulGautamSingh-testing/repro-21768)
DEBUG: Found 0 comments (repository=RahulGautamSingh-testing/repro-21768)
DEBUG: Ensuring comment "Renovate is disabled" in #1 (repository=RahulGautamSingh-testing/repro-21768)
 INFO: Comment added (repository=RahulGautamSingh-testing/repro-21768)
       "issueNo": 1,
       "topic": "Renovate is disabled"
 INFO: Repository is disabled - skipping (repository=RahulGautamSingh-testing/repro-21768)
```
