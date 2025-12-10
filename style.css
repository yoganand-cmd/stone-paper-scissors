function play(userChoice) {
    let choices = ["stone", "paper", "scissors"];
    let computerChoice = choices[Math.floor(Math.random() * 3)];

    let result = "";

    if (userChoice === computerChoice) {
        result = "Draw! Both chose " + userChoice;
    } else if (
        (userChoice === "stone" && computerChoice === "scissors") ||
        (userChoice === "paper" && computerChoice === "stone") ||
        (userChoice === "scissors" && computerChoice === "paper")
    ) {
        result = "You Win! Computer chose " + computerChoice;
    } else {
        result = "You Lose! Computer chose " + computerChoice;
    }

    document.getElementById("result").innerHTML = result;
}
