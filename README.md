# dadi-makeflow



on MASTER machine:
`makeflow --jx demo_inf.jx -T wq -N DADI`


Send workers 
`work_queue_factory -T local -w 2 -W 8 128.196.142.36 9123`
