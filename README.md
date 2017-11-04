# jsontohtml

To convert a JSON file which has comma after a record to with out a comma. As an example, 
from :
},
{
to:
}
{

use below command.

sed '/10\ sec\ avg/s/\(.*\),/\1 /g' vioperfauxdb3 >> vioperfauxdb3.json

This python script will simply convert a json file to html file. 
