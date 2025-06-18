## Debug Logs

```debug
DEBUG: Generating yarn.lock for . (repository=Rahul-renovate-testing/repro-36407, branch=renovate/express-5.x)
DEBUG: Spawning yarn install to create yarn.lock (repository=Rahul-renovate-testing/repro-36407, branch=renovate/express-5.x)
DEBUG: No node constraint found - using latest (repository=Rahul-renovate-testing/repro-36407, branch=renovate/express-5.x)
DEBUG: Enabling global cache as zero-install is not detected (repository=Rahul-renovate-testing/repro-36407, branch=renovate/express-5.x)
DEBUG: Executing command (repository=Rahul-renovate-testing/repro-36407, branch=renovate/express-5.x)
       "command": "yarn install --mode=update-lockfile"
DEBUG: exec completed (repository=Rahul-renovate-testing/repro-36407, branch=renovate/express-5.x)
       "durationMs": 1533,
       "stdout": "➤ YN0000: · Yarn 4.8.0\n➤ YN0000: ┌ Resolution step\n➤ YN0085: │ + express@npm:5.1.0, cookie@npm:0.7.2\n➤ YN0085: │ - cookie@npm:0.6.0, debug@npm:4.3.6, express@npm:5.0.0, methods@npm:1.1.2, ms@npm:2.1.2, nodejs@workspace:., qs@npm:6.13.0, utils-merge@npm:1.0.1\n➤ YN0000: └ Completed in 0s 861ms\n➤ YN0000: ┌ Fetch step\n➤ YN0013: │ 2 packages were added to the project (+ 218 KiB).\n➤ YN0000: └ Completed in 0s 216ms\n➤ YN0000: ┌ Link step\n➤ YN0073: │ Skipped due to mode=update-lockfile\n➤ YN0000: └ Completed\n➤ YN0000: · Done with warnings in 1s 108ms\n",
       "stderr": ""
DEBUG: yarn.lock needs updating (repository=Rahul-renovate-testing/repro-36407, branch=renovate/express-5.x)
```
