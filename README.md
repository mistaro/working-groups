# Working Groups

As described in the ONNX [governance](https://github.com/onnx/onnx/tree/master/community#wg---working-groups), Working Groups (WGs) are temporary groups formed to address issues that cross SIG boundaries. Working Groups have a have a clear goal measured through specific deliverables and disband after the goal is achieved. Working groups do not own artifacts long term; they create specifications, recommendations, and/or code implementations for submission to the relevant SIGs for approval and acceptance.

## Proposing a new working group
New Working Groups are created when there is sufficient interest in a topic area and someone volunteers to be the chair for the group and submits a proposal to the steering committee. The chair facilitates the discussion and helps synthesize proposals and decisions. 

## Joining a working group
Working Groups have most of their discussions on Gitter. If you are interested in participating, please join the discussion in the respective Gitter room.

You can find the schedule of meetings on the [LF AI wiki](https://wiki.lfai.foundation/pages/viewpage.action?pageId=18481196)

Working Groups store these artifacts, including meeting notes, in this repository. The working group leads have merge permissions on the repo but should only handle PRs related to their working group.

## Active working groups

| Working Group      | Objectives    |
| ------------------ | ------------- |
| [Training](https://gitter.im/onnx/training) | Expand ONNX to support training as well as inference |
| [Data Pipelines](https://gitter.im/onnx/pipelines) | Define new operators for processing the data that goes in and comes out |
| [Release](https://gitter.im/onnx/Releases) | Document release process, enhance release verification, identify fixes for release builds, recommend release operational guidelines in communication, frequency, scope, dependencies, and schedule |

## Completed working groups

| Working Group      | Objectives    | Status |
| ------------------ | ------------- | ------ |
| [Control Flow and Loops](https://gitter.im/onnx/ControlFlowWG) | Enable dynamic control structures to enable advanced models for NLP, speech, and video/image processing | Completed - If, Loop, and Scan operators were added in ONNX 1.3 release. |
| [Quantization](https://gitter.im/onnx/quantization) | Enhance ONNX to support quantized data types and operators on a variety of runtimes and hardware devices | Completed - added in ONNX 1.5 release. |
| [Foundation](https://gitter.im/onnx/foundation) | Identify and evaluate non-profit foundation options for the ONNX consortium.  Execute on best option. | Completed - ONNX joined LF AI in November 2019|

## Inactive working groups

| Working Group      | Objectives    | Status |
| ------------------ | ------------- | ------ |
| [Testing/Compliance](https://gitter.im/onnx/test_compliance) | Create tools, tests and APIs to ensure models and backends comply with the ONNX specification | became part of the ArchInfra SIG for now |
| [Edge/Mobile](https://gitter.im/onnx/edge) | Enable deployment of ONNX models to edge platforms by identifying the ONNX operators that must be supported by mobile and IoT runtimes, defining tool chain requirements, and contributing to ONNX compatibility tests | Stopped as of January 2020 |
