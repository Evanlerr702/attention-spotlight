# Beyond the Spotlight

An interactive football attention model for **Represent a Phenomenon with Code and AI**.

## Run

Download this repository and open `index.html` in a browser. No installation, account, build step, or external dependency is required.

## Explore

- Choose a favorite player.
- Adjust preference, recent-performance, and possession weights.
- Set attention capacity to one or two players.
- Advance through the same four-stage fictional attack.
- Compare highlighted players with off-ball contributions outside focus.
- Save snapshots and export them as CSV before refreshing.

## Model

`score = 1 + preferenceWeight × favoriteIndicator + performanceWeight × scriptedPerformance + possessionWeight × possessionIndicator`

Weights are slider values divided by 100. The highest-scoring one or two players are highlighted. Ties use ascending shirt numbers for repeatability. Score shares are not measured viewing time.

## Scope and limitations

This is an AI-assisted classroom prototype, not an eye tracker or a validated psychological model. All players, actions, and performance values are fictional. No real spectator experiment was conducted. Outside focus does not mean unseen, and restricting attention to one or two players already builds exclusion into the model.

## Files

- `index.html`: complete English HTML/CSS/JavaScript prototype.
- `design-sketch.svg`: conceptual interface diagram, not a browser screenshot.

## Optional GitHub Pages hosting

In the repository settings, open **Pages**, select **Deploy from a branch**, choose the `main` branch and `/ (root)`, then save. Availability depends on repository visibility and the account plan.
