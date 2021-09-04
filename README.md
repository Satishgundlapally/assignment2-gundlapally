# Dollar general,Maryville
1.  Take left on ElM St towards S Main St.
2. Take a slight right near W Lincoln St
3. continue straight for 80 miles on the street
4. merge with highway no 71
   1. pass on finish line gas station near St. joseph
   2. keep straight for 50 miles .
   3. Take exist 75 for kansas city road.
   4. Now, we are on Dwight D. Eisenhower Hwy towards Gateway arch.
5. take a U Turn near wentzville crossroads
   1. turn left go straight for 10 miles
   2. pass on ramp road
   3. take right
   4. go straight
5. now, your destination is on Left.
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

------

----

# pithy quotes

 > Creativity is intelligence having fun. —  *Albert Einstein*

 >> If you cannot do great things, do small things in a great way. – *Napoleon Hill*

 ----


 ---
 # code fencing

A depth-first search (DFS) is an algorithm for traversing a finite graph. DFS visits the child vertices before visiting the sibling vertices; that is, it traverses the depth of any particular path before exploring its breadth. A stack (often the program's call stack via recursion) is generally used when implementing the algorithm
'''
 vector<vector<int>> adj;  // adjacency list representation
int n; // number of nodes
int s; // source vertex

queue<int> q;
vector<bool> used(n);
vector<int> d(n), p(n);

q.push(s);
used[s] = true;
p[s] = -1;
while (!q.empty()) {
    int v = q.front();
    q.pop();
    for (int u : adj[v]) {
        if (!used[u]) {
            used[u] = true;
            q.push(u);
            d[u] = d[v] + 1;
            p[u] = v;
        }
    }    
}

} else {
    vector<int> path;
    for (int v = u; v != -1; v = p[v])
        path.push_back(v);
    reverse(path.begin(), path.end());
    cout << "Path: ";
    for (int v : path)
        cout << v << " ";
}
'''
code: https://cp-algorithms.com/graph/breadth-first-search.html#toc-tgt-0    