go-dirty-word-filter
====================

go-dirty-word-filter 
脏字过滤

t:=NewTrie()

t.Inster("脏话")

t.Inster("mb")

s:=t.Replace("不能说脏话也不能说mb")

fmt.Println(s)

输出结果：
不能说**也不能说**


