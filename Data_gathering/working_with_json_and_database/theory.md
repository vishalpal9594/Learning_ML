<h2>working with json</h2>
its working is similar to csv formate of working for reading json data we use<h4>pd.read_json("file_name")</h4>
we can also get data available to any url by using <h4>pd.read_json("url")</h4>


<br>
<h2>working with Databases</h2>
!pip install mysql.connector<br>
import mysql.connector <br>
conn = mysql.connector.connect(host='localhost',user='root',password='',database='world')
<br><br>
df = pd.read_sql_query("SELECT * FROM countrylanguage",conn)
