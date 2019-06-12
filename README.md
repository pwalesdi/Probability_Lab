# Probability_Lab

This lab was interesting and much more intuitive than the previous lab. I didn't like how the lab was centered around this idea that your boss isn't mathy and so you should change the way you present the data to fit his understanding. I personally believe that it would be more beneficial to learn the skills of conveying the "proper" information well so that a non-mathy person can understand it. I think that this skill is much more valuable than conveying information is a less accurate way to satisfy the persons resistance to learning. Just my thoughts but I am open to trying both.

OTHER CODE
Below is some code I used to attempt to do question 6 in a different manner. It didn't end up running the way I had hoped but I think that I was on the correct track. I found a different method instead that returned the same result:

# import seaborn as sns
# m_elixir = [] # Prize 1
# pendant = [] # Prize 2
# armor = [] # Prize 3
# bronze_coin = [] # Prize 4
# prizes = [1,2,3,4]
# # version_2_box = np.random.choice(prizes, 1, p=[0.01, 0.09, 0.30, 0.60]) # open_box_trial is a variable that represents opening a box once
# # elixer_tries = 0 # a variable representing how many boxes you open before getting an elixer
# # pendant_tries = 0 
# armor_tries = 0
# # coin_tries = 0

# for i in range(10): 
#     elixer_tries = 0
#     pendant_tries = 0 
#     armor_tries = 0
#     coin_tries = 0
#     version_2_box = np.random.choice(prizes, 1, p=[0.01, 0.09, 0.30, 0.60])

#     #while version_2_box == 0:
#         #version_2_box = np.random.choice(prizes, 1, p=[0.01, 0.09, 0.30, 0.60])
#     if version_2_box==1:
#         elixer_tries += 1
#         m_elixir.append(elixer_tries)
        
#     elif version_2_box==2:
#         pendant_tries += 1
#         pendant.append(pendant_tries)
    
#     elif version_2_box==3:
#         armor_tries += 1
#         armor.append(armor_tries)

#     elif version_2_box==4:
#         coin_tries += 1
#         bronze_coin.append(coin_tries)
        
#     print(elixer_tries)
#     print(pendant_tries)
#     print(armor_tries)
#     print(coin_tries)

