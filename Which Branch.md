def which_prize (score):

    if score >=0 and score <=50:

        return ("Congratulations! You have won a wooden rabbit!")

    if score >= 51 and score <= 150:

        return ("Oh dear, no prize this time.")

    if score >= 151 and score <= 180:

        return ("Congratulations! You have won a wafer-thin mint!")

    if score >= 181 and score <= 200:

        return ("Congratulations! You have won a penguin!")



which_prize (58);
