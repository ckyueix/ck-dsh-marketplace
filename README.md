# CKYUEIX DSH Plugins

An independent, unofficial static plugin market for DeepSeek Harness.

**Market index:** https://raw.githubusercontent.com/ckyueix/ck-dsh-marketplace/main/index.json

## Available plugin

- **GLM Usage** — `@ckyueix/glm-usage@0.1.0` (DeepSeek Harness `0.2.1-rc.2`).
  Public npm package: https://www.npmjs.com/package/@ckyueix/glm-usage

- **Text Model Vision / 文本模型看图** — `@ckyueix/text-model-vision@0.2.0` (DeepSeek Harness `0.2.1-rc.3`; tested on macOS).
  Use images with your original text-only models; installation activates the plugin automatically.
  Select a vision service once in the plugin settings UI. No YAML, suffix models, or per-model setup.
  Public npm package and configuration: https://www.npmjs.com/package/@ckyueix/text-model-vision
  Same-session visual evidence is reused; image flows have no automatic retries. Recognition quality depends on the selected vision service.

## Add the market to DeepSeek Harness

In Plugins, enable the experimental **Custom plugin markets** feature.
Open Discover, choose **Add index source**, and enter the market index URL above.
Actual plugin installation requires a separate user confirmation.

This repository contains market metadata only, not the plugin's source code.
