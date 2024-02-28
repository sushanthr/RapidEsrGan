## RapidEsrGan

An implementation of ESRGAN using WebNN
See https://sushanthr.github.io/RapidEsrGan/

Fully offline, client side super resolution in your browser.

## Model details
Original model - https://github.com/xinntao/Real-ESRGAN

## Note on Browser Requirement (Chrome/Edge Canary on Windows)

WebNN is a new standard, in development.<br>
Check https://webmachinelearning.github.io/webnn-status/ for updates on your fav platform/browser.<br>


For now the latest canary of any chromium based browser:<br>
**Chrome/Edge Canary** on **Windows** has enough of the spec implemented for this implementation to work.<br>

You would also need the experimental WebNN API enabled.
```
chrome://flags/#web-machine-learning-neural-network
```
Please pay attention to the warning WebNN is an experimental API, proceed at your own risk.<br>
WARNING: EXPERIMENTAL FEATURES AHEAD! By enabling these features, you could lose browser data or compromise your security or privacy. Enabled features apply to all users of this browser. If you are an enterprise admin you should not be using these flags in production.

Chrome Canary https://www.google.com/chrome/canary/ <br>
Edge Canary https://www.microsoft.com/en-us/edge/download/insider?form=MA13FJ
