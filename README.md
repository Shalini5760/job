import random
adjectives = ["Dynamic", "Certified", "Global", "Lead", "Senior"]
roles = ["Meme", "Unicorn", "Blockchain", "AI", "Cloud"]
suffixes = ["Strategist", "Engineer", "Consultant", "Architect", "Specialist"]
adj = random.choice(adjectives)
role = random.choice(roles)
suffix = random.choice(suffixes)
job_title = f"{adj} {role} {suffix}"

print("Your fake job title is:", job_title)

while input("Want another one? (yes/no): ").lower() == "yes":
    job_title = f"{random.choice(adjectives)} {random.choice(roles)} {random.choice(suffixes)}"
    print("Your fake job title is:", job_title)
