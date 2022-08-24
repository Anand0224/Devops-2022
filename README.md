# Devops-2022

repo for devops

## How to use boto3 and AWS to translate

[boto3 Translate Docs] (https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/translate.html#Translate.Client.translate_text)

'''
response = client.translate_text(
    Text='string',
    TerminologyNames=[
        'string',
    ],
    SourceLanguageCode='string',
    TargetLanguageCode='string',
    Settings={
        'Formality': 'FORMAL'|'INFORMAL',
        'Profanity': 'MASK'
    }
)
'''

