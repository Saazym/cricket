# cricket
cricket
df.rename(columns = {'meta.data_version':'data_version', 'meta.created':'created_date', 'meta.revision':'revised',
       'info.dates':'date_info', 'info.gender':'sex', 'info.match_type':'match_type',
       'info.outcome.by.wickets':'outcome.by.wickets', 'info.outcome.winner':'outcome.by.winner', 'info.overs':'overs',
       'info.player_of_match':'player_of_match', 'info.teams':'teams', 'info.toss.decision':'toss.decision',
       'info.toss.winner':'toss.winner', 'info.umpires':'umpires', 'info.venue':'venue', 'info.city':'city',
       'info.outcome.by.runs':'outcome.by.runs', 'info.match_type_number':'match_type_number', 'info.neutral_venue':'neutral_venue',
       'info.outcome.method':'outcome.method', 'info.outcome.result':'outcome.result', 'info.outcome.eliminator':'outcome.eliminator',
       'info.supersubs.New Zealand':'supersubs.New Zealand', 'info.supersubs.South Africa':'supersubs.South Africa',
       'info.bowl_out':'bowl_out', 'info.outcome.bowl_out':'outcome.bowl_out'}, inplace=True)
