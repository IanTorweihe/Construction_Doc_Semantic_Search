# Construction_Doc_Semantic_Search
This Python script designed to extract location data from text that is not formatted for machine readability. An example application could be processing handwritten reports that have been scanned and the text extracted from the reports. The script reads the entire contents of a text file into a string variable, and then uses OpenAI's gpt-3.5-turbo natural language processing model to search the text for location data. First, it splits the text at a fixed marker, and then it searches a fixed number of lines for location data using a gpt powered binary classification switch. If it does not find any location data or the PDF formatting does not match the assumed formatting, the script uses the gpt model to search the entire text extraction for locations. The output is a string containing the location data found in the text.
