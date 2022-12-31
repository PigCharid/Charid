# 钱包维度

记录
时间：2022/12/27                                 人员：Charid
目前GameFi最为重要的两个维度就是活跃总用户量和交易量，目前GameFi相关文章的报道也是根据这两个指标维度进行展开，一般通过这两个维度的直观数据，反馈该项目的大体的健康状态。在整个GameFi赛道的分析中，新增用户也是一个评判这个赛道状态的维度标准。
直观能够评判项目的健康状态的数据都是项目方关心的数据，总的用户数量、代币价值、交易量、新用户、活跃用户以及多链部署的游戏，多链上的数据区分也很重要。这里的代币价值是该项目代币的代币价值，活跃用户也需要一个判定标准。
其实基础数据，就是用户和价值，这两个点每个也都可以展开，比如用户数据可以分成总用户，新增用户、活跃用户、用户流失、用户行为等等。价值的话可以分成总交易量、新增交易量、出金量等等。
有些是非重要的基础数据，可以直接当做一个看板维度进行分析展示，但是这样的话，停留在一个数据展示的基础上，我们前期也无法有明确的方式去帮助项目方去分析这个项目，没有大量的数据，也没有可靠的分析模型，那前期除了基础数据的展示，我们还可以把项目方十分关注的点和其他可能的影响因子进行组合分析。其实也是在帮我们平台跑数据，只要分析出了哪些因子可以影响项目价值，那我们就可以将这些影响因子作为评估项目健康的标准给项目方进行反馈。
[图片]
币价的走势币价这个维度是项目方比较在乎的点，但是直观反馈币价，肯定没什么作用，对比分析，就能直观的反馈出问题在哪里。可以考虑当做一个发散点。
基础直观可展示的数据就那么几种，更多的是我们要提炼出来适配项目方的维度。
项目方关心的数据
用户、交互情况、本项目代币币价
基础数据
  将项目方关心的数据进行细分
用户层级
  - 总用户：和合约交互过的地址数量，留一个板位展示直观的数据即可，添加按照不同链划分的
  - 新增用户：这个可以按照时长，一天、一周、一个月不同状况显示数据
  - 活跃用户：这个就是需要一个鉴定标准了，完全根据链上的数据去判断活跃的话，并不是很全面，比如，有些项目，不需要每天都进行合约交互，那这个活跃用户的定义就不是很好下定。设置的太高的话，活跃用户的呈现数量就很少，设置的太低的话，活跃用户的统计失去了实际的价值意义。一种方式使我们定一个规则，有两次合约交互的用户都算活跃用户，另外一种就是让项目方定义，比如可以定义和接口A交互5次的用户算活跃用户。
  - 用户流增长率：也是需要一个鉴定标准，同期用户总数/上一期用户总量*100%
  
交互层级
  - 交易总量：和合约交互的次数，留一个板位展示直观的数据即可，添加按照不同链划分的
  - 新增交易量：这个可以按照时长，一天、一周、一个月不同状况显示数据
  - 成交额：统计改GameFi全部、每天、每周、每月的成交额度，就是别人在GameFi里面花了多少钱，一般GameFi付费的代币会不一样，用主币或者自己的项目代币，如果是小众的代币的话，价值的波动比较大，直接展示这个项目收益的代币数量，不转化成法币价值。这里。也能按照不同链把不同链上的数据隔开。
用户行为
  用户行为是高阶维度，可以帮助项目方了解到自己用户的口味。
  - 可以分析自己项目的这些用户NFT的持有情况、Token持有情况，这个部分设置成自主填入合约地址会好一些，也不知道项目方想看用户有有哪些Token和NFT。让项目方填写对应的NFT和Token合约地址进行刷选查看。
  - 其他更多有实际意义的用户行为还要边做边想了
  
组合分析
  - 币价走势+日交易量
  - 日成交额+日新增用户   
  这种需要融入很强的主观意愿的对比分析，我们可以开设2-3个模版案例，后面有更好的组合分析方式再继续添加，更多的还是提供一些数据，让项目方去自定义组合。

地址分析维度
上面罗列的维度是在进行项目层级的分析，但是数据都是通过项目的链上地址数据展示出来的，有一些维度可以当做地址维度进行分析，目前链上的数据格式比较的固定，我这边可以想到的有价值的一些点就是这些。
  - 活跃用户
  - 用户行为第一点也可以放这里当做用代币价值：分析和自己项目交互的钱包地址的价值，也是项目方判断和自己项目进行交互的地址情况。
  - 目前想不到更好的更高阶的维度分析，可以先放这两个，或者原本的几个维度也可以保留以一些，可以沟通确认一下
    
    
