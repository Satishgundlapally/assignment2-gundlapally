# Dollar general,Maryville
>> 1.  Take left on ElM St towards S Main St.
>> 2. Take a slight right near W Lincoln St
>> 3. continue straight for 80 miles on the street
>> 4. merge with highway no 71
>>   1. pass on finish line gas station near St. joseph
>>   2. keep straight for 50 miles .
>>   3. Take exist 75 for kansas city road.
>>   4. Now, we are on Dwight D. Eisenhower Hwy towards Gateway arch.
>> 5. take a U Turn near wentzville crossroads
>>   1. turn left go straight for 10 miles
>>   2. pass on ramp road
>>   3. take right
>>   4. go straight
>> 5. now, your destination is on Left.
* A Backpack
* AIR Tight water proof bags
   * For storing food items
    * laundry
   * to keep personal documents, gadgets.
* REusable water tumbler


![kink of AboutMe](https://github.com/Satishgundlapally/assignment2-gundlapally/blob/main/AboutMe.md)


------

# TABLES

The following table shows that receipes which are present in hyderabad.

| food            | location      |  amount |
| ---             | ---           | ---:    |
| sofiana biryani | hyderabad     | $5      |
|Bagara eggmasala | kothapet      | $3      |
|mutton dalcha    | secundrabad   | $ 6     |
| chicken biryani | kphb          | $4      |



----

# pithy quotes

 > Creativity is intelligence having fun. —  *Albert Einstein*

 > If you cannot do great things, do small things in a great way. – *Napoleon Hill*

 ----


 
 # code fencing

>  A In computer science, graph traversal (also known as graph search) refers to the process of visiting (checking and/or updating) each vertex in a graph. Such traversals are classified by the order in which the vertices are visited. Tree traversal is a special case of graph traversal.
SOURCE CODE: https://ds1-iiith.vlabs.ac.in/exp/depth-first-search/graph-traversals.html

'''
 vector<vector<int>> adj;  // adjacency list representation<br>
int n; // number of nodes<br>
int s; // source vertex<br>
queue<int> q;<br>
vector<bool> used(n);<br>
vector<int> d(n), p(n);<br>
q.push(s);<br>
used[s] = true;<br>
p[s] = -1;<br>
while (!q.empty()) {<br>
    int v = q.front();<br>
    q.pop();<br>
    for (int u : adj[v]) {<br>
        if (!used[u]) {<br>
            used[u] = true;<br>
            q.push(u);<br>
            d[u] = d[v] + 1;<br>
            p[u] = v;<br>
        }
    }    
}

} else {<br>
    vector<int> path;<br>
   for (int v = u; v != -1; v = p[v])<br>
        path.push_back(v);<br>
    reverse(path.begin(), path.end());<br>
    cout << "Path: ";<br>
    for (int v : path)<br>
            cout << v << " ";<br>
}
'''
code: https://cp-algorithms.com/graph/breadth-first-search.html#toc-tgt-0    