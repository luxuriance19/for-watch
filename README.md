# for-watch
to see the feature
#### coupon_id
every dataset have a feature coupon_counts on coupon_id
#### merchant related feature
merchant_user_buy_count on merchant_id
#### user_id feature
user_consume_merchant_num\
user_consume_total\
user_received_coupon_total\
user_buy_use_coupon_total
#### other feature
user_merchant_count_on_merchant\
user_merchant_count_on_user\
merchant_coupon_type_total\
merchant_coupon_total\
user_merchant_coupon_total

## 注意转化率
改进：这里提取的转化率存在大部分转化率为1的值，类似广告点击率，这里应该采用贝叶斯平滑，对转化率做一个修正。
