# home-assistant-ci

## Why ci?
- I want to have the advantage of source control
- I don't want to copy stuff manually
- I don't want deploy invalid configuration to Home Assistant

## Setup

### Step 1: Setup GitLab CI
1. Create a gitlab repo
2. Place the .gitlab-ci.yml file in your GitLab repo
3. Move your Home Assistant config into the repo
4. Check if your build succeeds
5. Get a GitLab personal access token [howto](https://docs.gitlab.com/ee/user/profile/personal_access_tokens.html)

### Step 2: Home Assistant
1. Make sure that you have hass.io running
2. Open http://[your-homeassistant]/hassio/store
3. Add https://github.com/lazytesting/home-assistant-ci
4. Install home-assistant-ci

### Step 3: Configuration
[TODO]

https://gitlab.com/lazytesting/home-automation/-/jobs/artifacts/master/raw/dist/version.txt?job=release
https://gitlab.com/lazytesting/home-automation/-/jobs/artifacts/master/download?job=releasez

## Why GitLab and not GitHub
- I want to have my Home Assistant config in a private repo
- I love the CI part of GitLab
