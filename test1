option = {
    color:['#A0D911','#FA8C15','#EB2F95','#11C2C1','#B620E0','#6236FF','#2FC25B','#FACC14','#EF4864','#3196FA'],
    backgroundColor:{
        type: 'linear',
        x: 0,
        y: 0,
        x2: 1,
        y2: 1,
        colorStops: [{
            offset: 0, color: 'pink' // 0% 处的颜色
        },{
            offset: 1, color: 'green' // 100% 处的颜色
        }],
        },
    title : {
        text: '民生支出\n\n212.5亿元       162.3亿元       76.38%',
        subtext:'      预算数                           累计支出                   执行比例',
        textAlign:'auto',   
        textStyle:{
            color:'#44CAFF',
            fontSize:24,
        },
        subtextStyle:{color:'white',
            fontSize:15,},
        x:10,
        y:10
    },
    tooltip : {
        trigger: 'item',
        formatter: "{a} <br/>{b} : {c} ({d}%)"
    },
    legend: {
        orient: 'vertical',
        left: 'left',
        show:false,
    },
    series : [
        {
            name: '访问来源',
            type: 'pie',
            radius : '40%',
            center: ['50%', '60%'],
            data:[
                {value:100, name:'农业水事务'},
                {value:100, name:'城乡社区'},
                {value:100, name:'节能环保'},
                {value:100, name:'卫生健康'},
                {value:100, name:'社会保障与就业'},
                {value:100, name:'文体传媒'},
                {value:100, name:'科学技术'},
                {value:100, name:'教育'},
                {value:100, name:'公共安全'},
                {value:100, name:'住房保障输出'},
            ],
            
            labelLine:{
                length:40,
                length2:120,
                lineStyle:{
                    color:'white'
                },
            },
            itemStyle: {
                emphasis: {
                    shadowBlur: 10,
                    shadowOffsetX: 10,
                    shadowColor: 'rgba(0, 0, 0, 0.5)'    
                }
                },
            label:{
                formatter:'{b} {d}%\n\n',
                fontSize:18,
                padding: [0, -140],
                color:'white',
            }
        }
    ]
 };
