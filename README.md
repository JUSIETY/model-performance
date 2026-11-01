# Local model performance dashboard

H1 and Arcana model versions, checkpoint evaluations and iteration-level training statistics.

The site loads compressed per-run histories on demand. Training metrics and independent evaluation results are shown separately. Missing values are not inferred. Machine-local absolute paths and model weights are not published.

Generated from local reports and TensorBoard event files. The last-sync time is displayed in the dashboard. Shutdown-time network transfers are best effort; the local sync command retries on the next scheduled run. The dedicated update-and-shut-down shortcut completes the upload before requesting shutdown.
