# download-setup-actions
Download setup actions for self-hosted runners without internet access.

---

## Usage
1. Clone the repo;
2. Edit the workflow, replace the setup step with the action you want to download, then push;


```yaml
      - name: Setup Python
        uses: actions/setup-python@v3
        with:
          python-version: "3.10"
```

3. Download the artifact.
