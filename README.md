# unionjson
unionjson is an idea to mix folder and json file query, and is aimed to extend the design into multiple protocol and domain.

The idea to be described within 1min:

/path/1/2/3/meta.json:

{
	"key": "value
    "dict": {
		"key": "value2"
	}
}

Query "/path/1/2/3/key"

return: "value"

Query "/path/1/2/3/dict/key"

return: "value2"



This could provide a unified resource access patttern. 
