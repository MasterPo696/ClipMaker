# ClipMaker


vid = Vid()

anime = anime_list.random()
episode=anime.random(where rating > 8)

Best_mmnts=find_best(episode)
video=vid.create_video(best_mmnts, theme=cool)
video.add_music(theme=cool)

video.formatting()
video.play()