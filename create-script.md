You are a [ROLE], and you are tasked to create a [LANGUAGE] script. 

The script's purpose is to [SCRIPT_PURPOSE]:
- The script must [INCLUSION]:
    - The script must use the following libraries: [COMMA_SEPARATED_LIBRARIES_LIST].
- The script must not [EXCLUSION].

The script requires to access data from:
- [DATA_SOURCE_1]
    - Accessible via [DATA_ACCESS_METHOD]
    - Authentication is [REQUIRED/NOT REQUIRED] to access the data:
        - The authentication method is [AUTHN_METHOD]
        - The credentials are stored in [SECRETS_KEY_VAULT]
    - Here is an example of the content of the data source [DATA_SOURCE_FORMAT].
- [DATA_SOURCE_2]
    - Accessible via [DATA_ACCESS_METHOD]
    - Authentication is [REQUIRED/NOT REQUIRED] to access the data:
        - The authentication method is [AUTHN_METHOD]
        - The credentials are stored in [SECRETS_KEY_VAULT]
    - Here is an example of the content of the data source [DATA_SOURCE_FORMAT].

The script requires the following arguments:
- [ARGUMENTS_1], provided by [INPUT_SOURCE], in the [FORMAT] format.
- [ARGUMENTS_2], provided by [INPUT_SOURCE], in the [FORMAT] format.
- [ARGUMENTS_3], provided by [INPUT_SOURCE], in the [FORMAT] format.
- [ARGUMENTS_4], provided by [INPUT_SOURCE], in the [FORMAT] format.

The script is expected to print the following data on the stdout: [STDOUT_OUTPUT].

The script is expected to save the following data in a [FILETYPE] file: [FILE_OUTPUT]. 
- The filename should use the following pattern [FILENAME_PATTERN]
- Append the today's date in the following format [DATE_FORMAT] to the filename. 
- The file should be saved in [PATH].

Make sure to comment the code to explain how it works. 
Make sure to use secure coding practices.
Make sure to use dependencies that are safe and well maintained.
Make sure to make it verbose enough so I know the state of execution while observing the STDOUT.
From now on, anytime your response contains code, make sure to print the entire code.

Ask me any questions that would help you clarify my prompt and help you achieve this request.