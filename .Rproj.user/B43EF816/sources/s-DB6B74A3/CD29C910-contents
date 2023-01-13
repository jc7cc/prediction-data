to_base <- function(amount, base) {
  amount / 10 ** base
}

check_result <- function(position, lock_price, close_price) {
  if (position == 'bull' && close_price - lock_price > 0) {
    res <-  "win"
  } else if (position == 'bear' && close_price - lock_price < 0) {
    res <- "win"
  } else {
    res <- "lose"    
  }
  res
}

get_payout_rate <- function(amount, reward) {
  reward / amount
}

get_side <- function(lock, close) {
  ifelse(lock > close, 'bear', 'bull')
}

# total <- to_base(14516079987993793300, 18)
# reward_base <- to_base(8822077036108363979, 18)
# reward <- to_base(14080597588353979501, 18)
# bear <- to_base(5694002951885429321, 18)
# bull <- to_base(8822077036108363979, 18)
# 
# reward / bear
# reward / bull

