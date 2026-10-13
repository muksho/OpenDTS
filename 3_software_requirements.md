# Software Requirement Specification (SWS)

| ID | Description | Status | Upstream Trace | Downstream Trace |
| :--- | :--- | :--- | :--- | :--- |
| <a id="SWR-201"></a>**SWR-201** | The software core shall interface with the OS biometric module via asynchronous C++ bindings to register callback events on a physical scan. | Approved | [SYR-101](./2_system_requirements.md#SYR-101) | [TC-401](./4_test_cases.md#TC-401) |
| <a id="SWR-202"></a>**SWR-202** | The application UI state engine must broadcast an `AUTH_SUCCESS` context event immediately upon a positive match token delivery. | Draft | [SYR-101](./2_system_requirements.md#SYR-101) | [TC-402](./4_test_cases.md#TC-402) |
| <a id="SWR-203"></a>**SWR-203** | The device software database layer shall use SQLCipher with an AES-256 block-cipher to wrap all localized telemetry queues. | Approved | [SYR-112](./2_system_requirements.md#SYR-112) | [TC-409](./4_test_cases.md#TC-409) |
| <a id="SWR-204"></a>**SWR-204** | The background power daemon shall throttle GPS polling frequency from 1Hz to 0.1Hz when the battery level drops below 15%. | In Review | [SYR-108](./2_system_requirements.md#SYR-108) | [TC-415](./4_test_cases.md#TC-415) |
