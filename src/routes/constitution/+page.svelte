<script>
    import { dues } from '$lib/utils/helper';
    let one, oneOne, oneOneOne, oneTwo, oneTwoOne, oneTwoTwo, oneTwoThree, oneTwoFour, oneTwoFive, oneThree;
    let two, twoOne, twoTwo, twoThree;
    let three, threeOne;
    let four, fourOne, fourTwo;
    let five, fiveOne;
    let six, sixOne, sixTwo, sixThree;
    let seven, sevenOne, sevenTwo, sevenThree;

    const goToSection = (section) => {
        const top = section.getBoundingClientRect().top + window.pageYOffset;
        window.scrollTo({left: 0, top, behavior: 'smooth'});
    }
</script>

<style>
    .constitution {
        position: relative;
        z-index: 1;
        width: 92%;
        max-width: 800px;
        margin: 8em auto 10em;
    }

    h1 {
        font-size: 2em;
        line-height: 1.2em;
        text-align: center;
        margin: 2em 0 1.5em;
    }

    h2 {
        font-size: 1.5em;
        line-height: 1.2em;
    }

    h3 {
        text-decoration: underline;
        font-size: 1.3em;
        line-height: 1.2em;
    }

    h4 {
        text-decoration: underline;
        margin-left: 2em;
        font-size: 1.2em;
        line-height: 1.2em;
    }

    h5 {
        margin-left: 6em;
        font-size: 0.8em;
        line-height: 1.1em;
    }

    .subBlock {
        margin-left: 2.4em;
    }

    .sectionHeading {
        margin: 4em 0 1.5em;
    }

    .subSectionHeading {
        margin: 1.5em 0 1.5em;
    }

    .underscore {
        text-decoration: underline;
    }

    .right {
        text-align: right;
    }

    .positionMaximums td {
        min-width: 3em;
    }

    .noUnderscore {
        text-decoration: none;
    }

    .clickable {
        cursor: pointer;
    }

    .clickable:hover {
        color: #00316b;
    }

    p {
        color: #777;
    }
</style>

<div class="constitution">
    <h1 class="noUnderscore">LEGENDS LEAGUE CONSTITUTION</h1>
    
    <h2 class="noUnderscore">TABLE OF CONTENTS</h2>

    <h3 class="noUnderscore clickable" on:click={() => goToSection(one)}>Section 1: League Concept</h3>
    <h3 class="noUnderscore clickable" on:click={() => goToSection(two)}>Section 2: League Fees</h3>
    <h3 class="noUnderscore clickable" on:click={() => goToSection(three)}>Section 3: Communication</h3>
    <h3 class="noUnderscore clickable" on:click={() => goToSection(four)}>Section 4: Penalty for Lack of Payment</h3>
    <h3 class="noUnderscore clickable" on:click={() => goToSection(five)}>Section 5: Startup</h3>
    <h3 class="noUnderscore clickable" on:click={() => goToSection(six)}>Section 6: Progressive Pots</h3>
    <h3 class="noUnderscore clickable" on:click={() => goToSection(seven)}>Section 7: Regular Season</h3>
    <h3 class="noUnderscore clickable" on:click={() => goToSection(seven)}>Section 8: Cup Competitions</h3>
    <h3 class="noUnderscore clickable" on:click={() => goToSection(seven)}>Section 9: Champions League</h3>
    <h3 class="noUnderscore clickable" on:click={() => goToSection(seven)}>Section 10: Federation Cup</h3>
    <h3 class="noUnderscore clickable" on:click={() => goToSection(seven)}>Section 11: Scoring Rules</h3>
    <h3 class="noUnderscore clickable" on:click={() => goToSection(seven)}>Section 12: Rosters</h3>
    <h3 class="noUnderscore clickable" on:click={() => goToSection(seven)}>Section 13: Taxi Squads</h3>
    <h3 class="noUnderscore clickable" on:click={() => goToSection(seven)}>Section 14: Injured Reserve</h3>
    <h3 class="noUnderscore clickable" on:click={() => goToSection(seven)}>Section 15: Trading</h3>
    <h3 class="noUnderscore clickable" on:click={() => goToSection(seven)}>Section 16: Rookie Draft</h3>
    <h3 class="noUnderscore clickable" on:click={() => goToSection(seven)}>Section 17: Free Agency</h3>
    <h3 class="noUnderscore clickable" on:click={() => goToSection(seven)}>Section 18: Tanking</h3>
    <h3 class="noUnderscore clickable" on:click={() => goToSection(seven)}>Section 19: Expansion</h3>
    <h3 class="noUnderscore clickable" on:click={() => goToSection(seven)}>Section 20: Owner Rules</h3>
    <h3 class="noUnderscore clickable" on:click={() => goToSection(seven)}>Section 21: Sportsmanship</h3>
    <h3 class="noUnderscore clickable" on:click={() => goToSection(seven)}>Section 22: Voting</h3>
    <h3 class="noUnderscore clickable" on:click={() => goToSection(seven)}>Section 23: Best Interest Clause</h3>
    <h3 class="noUnderscore clickable" on:click={() => goToSection(seven)}>Section 24: League Openings</h3>
    <hr />
     
    <h3 class="subSectionHeading" bind:this={oneOne}>1 League Concept</h3>
    
    <p>League Concept</p>
    
    <p Welcome to the World Federation of Fantasy Leagues. This will be a conglomerate of several individual leagues. Each league will have 12 teams, broken down into three divisions.</p>
    <p></p>    
    <p>As well as the competition cups, the Federation will celebrate its champions with a Champions League each year.</p>
    <p></p>   
    <p>Every two years, a Federation Cup will be held.</p>
    <p></p>  
    <p>The league will be run through Sleeper, with competition cups, Champions League, and Federation Cup tracked via Google Documents.</p>
    <p></p>
    <p>Owners will create teams with a city/state/region along with their mascot i.e. Anchorage Huskies. You may pick a city/state/province/region from anywhere in the world. I would prefer we don't use real teams, don't want to see a bunch of requests for Dallas Cowboys or Pittsburgh Steelers.</p>
    <p></p>
    <p>Teams will be placed in leagues based on their region. While it may not be the case, it is expected most regions will be in the United States, so there may be several US Leagues.</p>

    <h3 class="subSectionHeading" bind:this={oneTwo}>2 League Fees</h3>
    
    <p>LEAGUE SAFE and TEAMSTAKE will both be used for all dues.League safe is preferable, but if you are unable to use it, Teamstake is also being used. You may also use Teamstake if you have money in there.</p>
    <p></p>
    <p>League fees will be $25 per year. Teams will also be required to be paid for up to two seasons for an additional $25. This means teams will always be paid one season ahead. If a team is removed for cause (banishment), future buy-in money will be forfeited. If a team trades away the following year's 1st or second draft pick, and the owner leaves the league, the year's buy in is forfeited. If at any time an owner does not own a 1st round pick two seasons out, the owner must pay that season's dues. If an owner leaves the league and there are still no 1st round picks for that season, all future league fees will be forfeited. This money will be used to replace the owner.  Examples:</p/
        <ul>
            <li>In 2024 Team A trades away 2025 1st. Team A departs the league in 2025. 2025 fees are forfeited and used to bring in a new owner.</li>
            <li>In 2024 Team A trades away 2026 1st. Owner must pay 2026 dues. Team A departs the league in 2025. 2025 and 2026 league fees are forfeited and used to bring in a new owner.</li>
            <li>In 2024 Team A trades away 2026 1st. Owner must pay 2026 dues. During the season Team A trades for Team B 2026 1st. Team B must pay 2026 dues if no other 2026 1st exists on their team. Team A departs the league in 2025 and the team has 2025 1st and 2nd and a 2026 1st (even if it is not their own). All future league dues may be reimbursed.</li>
        </ul>
    <p></p>
    <p>If an owner is notified future payments are due, one week will be given to pay. If not paid during that week, a federation wide announcement will be made and another week given. If it is during the season, games after the first week will be counted as forfeits.</p>
    <p></p>
    <p>Any other reason (personal) money may be reimbursed.</p>
    <p></p>
    <p>League fees will be due on March 1st of each year.</p>
    <p></p>
    <p>The fees will be distributed according to the following:</p>
    <p></p>
    <p>10% of dues collected will be used towards competition cups, Champions League, Federation Cup, and progressive pots.</p>
    <p>The remaining dues collected will be distributed as follows:</p>
     <ul>
            <li>$100 Bowl Winner</li>
            <li>$75 Bowl Runner Up</li>
            <li>$50 3rd Place</li>
            <li>$30 division champions ($10 each)</li>
            <li>$10 Regular season best record</li>
            <li>$5 Regular season most points scored</li>
        </ul>
      

    <h4 bind:this={oneTwoTwo}>1.2.2 Lending Players Prohibition</h4>
    <div class="subBlock">
        <p>Any player traded from a team may not be re-acquired via trade within 6 weeks of the original trade. Any teams involved in this behavior will be subject to the aforementioned collusion punishments.</p>
    </div>
    
    <h4 bind:this={oneTwoThree}>1.2.3 Trade Deadline</h4>
    <div class="subBlock">
        <p>The trade deadline will be set for the Saturday of the week 11 games of the NFL season.</p>
    </div>
    
    <h4 bind:this={oneTwoFour}>1.2.4 Trade Restrictions</h4>
    <div class="subBlock">
        <p>You will not be able to trade draft picks that are more than 3 drafts away. For example, during the 2021 season you cannot trade any picks in or after the 2025 draft. You may only trade FAAB $ from the current season.</p>
    </div>
    
    <h4 bind:this={oneTwoFive}>1.2.5 Veto/Trade Process</h4>
    <div class="subBlock">
        <p>A total of 7 veto votes are required to veto a trade. Vetoes are only appropriate in instances of collusion or an egregious mismatch of value (i.e. CMC for a backup kicker). Not liking a trade does not warrant a veto.</p>
    </div>
    
    
    
    <h3 bind:this={oneThree}>1.3 Waiver Wire</h3>
    
    <p>FAAB Waiver wire system. Each team will begin the season with $100. $0 bids are allowed. Bids will process Thursdays and Sundays at 9AM EST.</p>

    <p>FAAB budgets will reset each season in January.</p>
    
    
    <h2 class="sectionHeading" bind:this={two}>Section 2 Drafting</h2>
    
    <h3 bind:this={twoOne}>2.1 Draft Order</h3>
    <p>The draft order each year will be a linear draft in reverse order of the previous year’s regular season standings.</p>

    <h3 bind:this={twoTwo}>2.2 Rookie Drafts</h3>
    <p>Rokkie drafts will consist of 3 round of drafting, with 5 minutes alotted for each pick. To make room for the incoming players, benches will be expanded by (5) spots. These spots will be removed in mid-August, at which point you will need to have cut the necessary players.</p>
    <p>Any spots not filled during the draft, can be filled immediately afterwards from the waiver wire.</p>
    
    <h3 bind:this={twoThree}>2.3 Draft Day Trades</h3>
    <p>If a trade is being made during the draft, one or both parties can alert the commissioner to pause the draft to allow for extra time to negotiate the trade.</p>
    
    <h2 class="sectionHeading" bind:this={three}>Section 3 Scoring System</h2>

    <h3 bind:this={threeOne}>3.1 Scoring System</h3>
    <p>The league scoring system breakdown is listed on the Sleeper fantasy app (for the most part, it follows typical .5PPR Scoring). The scoring system will never change without a majority league vote.</p>
    
    <h2 class="sectionHeading" bind:this={four}>Section 4 Postseason</h2>
    
    <h3 bind:this={fourOne}>4.1 Playoffs</h3>
    <p>At the end of the season 6 teams will make the playoffs. The first round of playoffs will commence in week 15. Each team that wins their division and the 4 wild card teams that finish with the best records, will receive a playoff berth. The 2 teams that win their division will receive a bye week in the first round of the playoffs. Each playoff matchup will only last one week and the winner will advance. Week 18 will not be used.</p>
    
    <h3 bind:this={fourTwo}>4.2 Seeding Tiebreakers</h3>
    <p>If two teams finish with the same record the tiebreakers will go as followed:</p>

    <ol>
        <li>Points For</li>
        <li>Head 2 Head Record</li>
        <li>Division Record</li>
        <li>Total Points Against</li>
        <li>Coin Flip</li>
        <li>Duel to the death</li>
    </ol>

    <h2 class="sectionHeading" bind:this={five}>Section 5 Tanking Policy</h2>
    
    <h3 bind:this={fiveOne}>5.1 League Tanking Policy</h3>
    <p>No team may intentionally leave starting roster spots empty. Any evidence of intentionally leaving roster spots empty in order to improve your draft position may be subject to punishment, including but not limited to the forfeiture of draft selections.</p>

    <h2 class="sectionHeading" bind:this={six}>Section 6 Replacing Managers</h2>
    
    <h3 bind:this={sixOne}>6.1 Removing Managers</h3>
    <p>Short of continuously failing to set a valid lineup, or confirmed collusion, no manager can be removed against their will. Participation, through the league chat, trade offers, and the waiver wire, is strongly encouraged but generally grounds for removal.</p>
    
    <h3 bind:this={sixTwo}>6.2 Replacing Managers</h3>
    <p>When a manager needs to be replaced, the commisiooners will try to find a suitable candidate with some connection to at least a portion of the existing managers. Priority will be placed on managers who are eager to take on a dynasty commitment and will be very active within the league.</p>
    
    <h3 bind:this={sixThree}>6.3 Replacement Incentive</h3>
    <p>In the event that a manager chooses to quit the league or is removed by a comissioner, an incoming manager is offered a 50% reductioon on their first year buy-in.</p>

    <h2 class="sectionHeading" bind:this={seven}>Section 7 League Finances</h2>
    
    <h3 bind:this={sevenOne}>7.1 League Dues</h3>
    <p>League dues are set at {dues}$. Dues are collected through <a href="https://www.leaguesafe.com/league/3949641">LeagueSafe</a> and collection will be sent out no later than the first of August. All managers must be fully paid up before the start of regular season. In the event that a manager fails to pay before the deadline, a 10% penalty will be addd to their payment and will go towards the payouts at the end of the year.</p>
    
    <h3 bind:this={sevenTwo}>7.2 Payout</h3>
    <p>League payout is structured as follows:</p>
    <ul>
        <li>1st place: {dues * 8}$</li>
        <li>2nd place: {dues * 3}$</li>
        <li>3rd place: {dues}$</li>
    </ul>
    <p>In the event that a manager was fined due to late payment, their extra fee will be added to the winner's payout. Similarly, if new managers come into the league and the payout is smaller, the difference will come out of the winner's prize.</p>
    
    <h3 bind:this={sevenThree}>7.3 Raising Dues</h3>
    <p>A ⅔ majority vote is required in order to raise league dues. In the event that a manager is no longer financially comfortable with the buyin, finding a co-manager to split the cost is reccomended.</p>

</div>
