# Integration samples

This repository contains samples for
[Application Integration](https://cloud.google.com/application-integration/docs).

## Overview

All integration samples are in the `src/` directory with the file format `<file
name>.integration.json`. If a sample has more than one file, all the files will
be available in the sample's directory in `src/`.

A `.json` file has the metadata of an integration. You can directly import the
`.json` file as an integration to your project and run the integration. For more
information, see
[Upload and download integrations](https://cloud.google.com/application-integration/docs/upload-download).

## How to: Execute an integration

To execute an integration, perform the following steps:

*   Click **Test** in the integration designer toolbar.</li>
*   In the **Confirm Publish and Test** dialog, click **Publish &amp; Test**.
*   After the integration completes successfully, the **Test Integration**
    dialog displays the completion message.

## How to: View execution logs

Application Integration generates execution log messages for each run of an
integration. The log messages contain information that can be helpful in
determining the status of each step in an integration, or to troubleshoot a
failed integration. For more information, see
[Execution logs](https://cloud.google.com/application-integration/docs/viewing-logs).
