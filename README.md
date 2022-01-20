# Netlifycode

Mattermost Netlify bot is an intermediary agent between your Netlify and mattermost account. It makes it easy to monitor and interact with your Netlify's resources all within your team's channel. Once integrated with your Mattermost channel, team can start recieving various Netlify notifications such as Netlify form submissions, build failures etc and can run commands to redeploy, see build stats, create hooks and much more.

Salient features are explained here

1.)Familiar interface : System admins can manage Netlify configuration right from the chat window with which they are
familiar with.
2.)Critical notification to team : Concerned teams are notified of the issue which makes it easier to plan and execute the
solution rapidly.
3.) System health and monitoring on the fly.

Development approach

Bot will be developed on Mattermost platform via https://developers.mattermost.com/integrate/plugins/. API's of Netlify will be integrated by Netlify Go API Client https://github.com/netlify/open-api#go-client

