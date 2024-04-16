# danger-js-dispatch-demo

```sh
gh api \
 --method POST \
 -H "Accept: application/vnd.github+json" \
 -H "X-GitHub-Api-Version: 2022-11-28" \
 /repos/7rulnik/danger-js-dispatch-demo/dispatches \
 -f "event_type=danger-js" -F "client_payload[ref]=hit-me-baby"
```
